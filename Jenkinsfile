pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        echo 'Checkout from GitHub'
        git 'https://github.com/agilas16/Maven.git'
      }
    }

    stage('Build') {
      steps {
        echo 'Build the code'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Package deploy'
      }
    }

  }
}