pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/GabrielNesteruk/JenkinsTester', branch: 'main')
      }
    }

    stage('Log directory') {
      steps {
        sh 'ls -la'
      }
    }

  }
}