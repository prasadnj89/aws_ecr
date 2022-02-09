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
        dockerNode(image: 'https://github.com/prasadnj89/my-dockerimage/blob/main/Dockerfile')
      }
    }

  }
}