pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
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