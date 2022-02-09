pipeline {
  agent any
  stages {
    stage('Clone git') {
      steps {
        git(url: 'https://github.com/prasadnj89/my-dockerimage/blob/main/Dockerfile', branch: '/main')
      }
    }

  }
}