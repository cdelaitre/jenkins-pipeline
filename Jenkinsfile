pipeline {
    agent any 

    stages {
        stage('Info') { 
            steps { 
                sh 'echo Info'
                sh "mvn --version"
            }
        }
        stage('Build') { 
            steps { 
                sh 'echo Build'
            }
        }
        stage('Test'){
            steps {
                sh 'echo Test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploy'
            }
        }
    }
}
