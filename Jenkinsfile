pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/Minahhh666/jenkins', branch: 'main')
      }
    }

    stage('build') {
      steps {
        sh 'python3 ops.py'
      }
    }

  }
}