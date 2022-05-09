pipeline {
    agent any

    stages {
        stage('Build') { 
            steps {
              echo 'building the app...'
            }
        }
    }
    stages {
          stage('test') { 
              steps {
                echo 'testing the app...'
              }
          }
      }
    stages {
          stage('deploy') { 
              steps {
                echo 'deploying the app...'
              }
          }
      }
}
