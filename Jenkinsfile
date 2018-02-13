pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
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
    Hello = 'Hello'
  }
}
