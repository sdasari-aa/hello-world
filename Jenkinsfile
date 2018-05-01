pipeline {
  agent {
    node {
      label 'jdk9'
    }
    
  }
  stages {
    stage('Deploy') {
      options {
        timeout(time: 30, unit: 'SECONDS')
      }
      input {
        message 'Should we continue?'
      }
      steps {
        echo 'Continuing with deployment'
      }
    }
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