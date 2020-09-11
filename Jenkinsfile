pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Hello from the Build Stage";
javac compileTest.java;
ls;'''
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