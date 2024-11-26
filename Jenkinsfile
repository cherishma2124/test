pipeline {
    agent any

    stages {
        stage('GitHub Access') {
            steps {
               echo ' build job: '
            }
        }

        stage('Java Program Execution') {
            steps {
                build job: 'Job2-JavaExecution'
            }
        }

        stage('Python Program Execution') {
            steps {
                build job: 'Job-3 Python'
            }
        }
    }
}