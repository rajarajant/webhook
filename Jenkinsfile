pipeline {
    agent any
 
    stages {
        stage('Welcome') {
            steps {
                echo 'Welcome to Jenkins'
                echo 'first work'
            }
        }
    }
 
    post {
        success {
            echo "Pipeline Executed Successfully"
        }
        failure {
            echo "Pipeline Execution Failed"
        }
    }
}
