pipeline {
    agent any 
    stages {
        stage('Git') {
            steps {
                git 'https://github.com/wellflag/react01.git'
            }
        }
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    } 
}
