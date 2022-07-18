pipeline {
    agent {
        node {
            lable 'NODEJS'
        }
    }
    stages {
        stage('Prepare Artifact') {
            steps {
                sh 'cd React'
            }
        }
        stage('Publish Artifacts') {
            steps {
                sh 'npm start'
            }
        }
    
    }   

}