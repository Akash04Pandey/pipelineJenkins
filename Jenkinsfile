pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "Build"

            }
        }
        stage('Test') {
            steps {
                echo 'Testing!' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying' 
            }
        }
    }
        post {
            always{
                echo 'Success or failure'
            }
            success{
                echo 'Success '
            }
            failure{
                echo 'failure'
            }
        }
}
