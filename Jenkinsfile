pipeline {
  agent any
  stages {
    stage('Clone git') {
      steps {
        git 'https://github.com/prasadnj89/my-dockerimage/blob/main/Dockerfile'
      }
    }

    stage('Build image') {
      steps {
        sh 'docker.build registry + ":$BUILD_NUMBER"'
      }
    }

  }
}