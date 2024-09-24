node ( 'ci-server' ) {
  if (binding.hasVariable("$TAG_NAME")) {
    stage('Build Code') {
      print 'ok'
    }
    stage('Release Software') {
      print 'ok'
    }
}   else {
    stage('Lint Code') {
      print 'ok'
    }
    if(env.BRANCH_NAME != 'main') {
      stage('Run Unit tests') {
        print 'OK'
      }
      stage('Run Integration tests') {
        print 'OK'
      }
    }
    stage('Sonar Scan Code Review') {
      print 'ok'
    }
  }
}
