pipeline {
    agent any 
    stages {
        stage('Git') {
            steps {
                git 'https://github.com/wellflag/react01.git'
            }
        }
        stage('Install') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Build') { 
            steps {
                sh 'npm run-script build ' 
            }
        }
    } 
}
