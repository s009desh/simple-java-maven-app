pipeline {
    agent any

    stages {
        stage('dev from github') {
            steps {
                echo 'Hello World from dev enviroment'
            }
        }
        
        stage('UAT from github') {
            steps {
                echo 'Hello from UAt enviroment'
            }
        }
        
        stage('prod from github') {
            steps {
                echo 'Hello from pod enviroment '
            }
        }
    }
}
