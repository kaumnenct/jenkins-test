pipeline {
    agent any

    stages {
        stage('Build') { 
            steps {
              echo 'building the app...'
                nodejs('NodeJS Jenkins') {
                    sh 'npm install ./app'
                }
            }
        }
          stage('deploy') { 
              steps {
                echo 'deploying the app...'
                  nodejs('NodeJS Jenkins') {
                    sh 'npm run build'
                    sh 'npm start'
                  }
              }
          }
    }
}
