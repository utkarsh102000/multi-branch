pipeline {
  agent {label 'demo-docker-slave'}
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
