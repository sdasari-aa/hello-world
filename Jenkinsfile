pipeline {
  agent {
    node {
      label 'jdk9'
    }
    
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Srini'
  }
}