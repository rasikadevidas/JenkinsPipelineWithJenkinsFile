pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Test Build'
          }
        }

        stage('Test') {
          steps {
            echo 'Test Test'
          }
        }

      }
    }

    stage('Deploy ') {
      steps {
        echo 'Deploying app in server'
      }
    }

  }
}