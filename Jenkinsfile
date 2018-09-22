pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello git'
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
  }
  environment {
    Test = 'Test'
  }
}
