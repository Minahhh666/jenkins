pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/Minahhh666/jenkins', branch: 'main')
      }
    }

    stage('Build') {
      steps {
        sh 'python ops.py'
      }
    }

  }
}