pipeline {
  agent {label 'linux'}
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  stages {
    stage('hello') {
      steps {
        echo "hello"
      }
    }
  }
}
