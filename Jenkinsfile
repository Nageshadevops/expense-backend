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
    stage('Run Unit tests') {
      print 'ok'
    }
    stage('Run Integration tests') {
      print 'ok'
    }
    stage('Sonar Scan Code Review') {
      print 'ok'
    }
  }
}
