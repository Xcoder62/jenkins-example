pipeline {
  agent {
    docker {
      image 'python:3.5.1'
      args 'sh \'python --version\''
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'python --version'
        echo 'Hello from the pipeline'
      }
    }

  }
}