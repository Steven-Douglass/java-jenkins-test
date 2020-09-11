pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello from the Build Stage'
        sh 'ls'
      }
    }

    stage('Test') {
      steps {
        echo 'Hello from the Test Stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Hello from the Deploy Stage'
      }
    }

  }
}