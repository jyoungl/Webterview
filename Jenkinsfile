pipeline {
    agent any

    stages {
        stage('Prepare') {
            steps {
              dir('workspace'){
                checkout scm
              }
            }

            post {
                success {
                  echo " prepare success"
                }
                failure {
                  echo "prepare fail"
                }
            }
        }
        stage('Frontend Build') {
          steps {

          }
        }
    }
}