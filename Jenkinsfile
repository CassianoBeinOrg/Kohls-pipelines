pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello World'
        sleep 5
        sh 'java -version'
      }
    }
    stage('Create image') {
      parallel {
        stage('Create image') {
          steps {
            echo 'Creating container image'
          }
        }
        stage('Test') {
          steps {
            echo 'Tests'
          }
        }
      }
    }
    stage('Push Image to registry ') {
      steps {
        sleep 20
      }
    }
  }
}