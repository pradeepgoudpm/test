pipeline {
  agent any
  stages {
    stage('Dev') {
      parallel {
        stage('Dev') {
          steps {
            echo 'dev environment'
          }
        }

        stage('Test') {
          steps {
            echo 'test environment'
          }
        }

        stage('Acc') {
          steps {
            echo 'acceptance environment'
          }
        }

        stage('Prod') {
          steps {
            echo 'prod environment'
          }
        }

      }
    }

  }
}