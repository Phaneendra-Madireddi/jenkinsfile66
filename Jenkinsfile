pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'I wan to Build'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'I want to Print'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Deploy'
          }
        }

      }
    }

  }
}