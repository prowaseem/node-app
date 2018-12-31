pipeline {

  agent none

  stages {
    stage('Front-end') {
      agent {
        docker {
          image: 'node:8-alpine'
        }
      }
      steps {
        sh 'node --version'
      }
    }
  }
}