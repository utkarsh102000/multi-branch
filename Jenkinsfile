pipeline {
  agent {label 'docker-agent-python'}
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
