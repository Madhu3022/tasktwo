pipeline {
    agent any

    stages {
        stage('Building image') {
            steps {
                sh 'docker build . -t basicimage:latest'
            }

        }
       stage('Running image'){
           steps{
               sh 'docker run basicimage:latest'
             }
          }
    }
}
