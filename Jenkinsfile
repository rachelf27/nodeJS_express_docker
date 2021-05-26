pipeline {
  agent {
    docker {
      image 'node:16-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'node --version'
      }
    }

    stage('Test') {
      steps {
        echo '"Testing: Test stage. "'
      }
    }

    stage('End') {
      steps {
        echo '""Testing: build completed"'
      }
    }

  }
}