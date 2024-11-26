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
        sh 'docker pull ranjitsinghneo/dependency-checker:latest'
        sh 'docker run -it --rm --name dependency-checker --volume `pwd`:/app/files dependency-checker:latest'
      }
    }

    stage('Release') {
      steps {
        echo 'This is Release stage'
      }
    }
  }
}
    
