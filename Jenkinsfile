pipeline {
  agent {
    docker {
      image 'python:3-slim'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'python --version'
        echo 'Hello from the pipeline (Build/dev)'
      }
    }

    stage('Test') {
      steps {
        echo 'hello from Staging/Test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Hello from Production'
      }
    }

  }
}