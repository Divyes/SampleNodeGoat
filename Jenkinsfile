pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'This is Build stage'
      }
    }

    stage('Test') {
      steps {
        sh 'pwd'
        sh 'ls -al'
      }
    }

    stage('Release') {
      steps {
        echo 'This is Release stage'
      }
    }
  }
}
    
