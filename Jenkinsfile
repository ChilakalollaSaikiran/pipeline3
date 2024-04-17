pipeline {
    agent any
    stages {
        stage('Deploy-Dev'){
            steps {
                echo'Hello'
            }
        }
        stage('Deploy-QA'){
            steps {
                echo'QA'
                input"Does the staging environment look ok?"
            }
        }
        stage('Deploy-Production'){
            steps {
                echo'Production'
            }
        }
    }
}
