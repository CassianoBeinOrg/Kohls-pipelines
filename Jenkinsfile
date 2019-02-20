pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello World'
        sleep 2
        sh 'java -version'
      }
    }
    stage('Create image') {
      steps {
        echo 'Creating container image'
      }
    }
    stage('Push Image to registry ') {
      steps {
        sleep 4
      }
    }
  }
}
