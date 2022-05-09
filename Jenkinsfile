pipeline {
    agent any

    stages {
        stage('Build') { 
            steps {
              echo 'building the app...'
                nodejs('NodeJS Jenkins') {
                    sh 'cd app'
                    sh 'npm install'
                }
            }
        }
          stage('deploy') { 
              steps {
                echo 'deploying the app...'
              }
          }
    }
}
