pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Hello from the Build Stage";
javac compileTest.java;'''
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