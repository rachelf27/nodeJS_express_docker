pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'node app.js'
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