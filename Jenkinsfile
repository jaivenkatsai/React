pipeline {
     agent any
     stages {
        stage("one") {
            steps {
                sh "sudo npm install"
                sh "sudo npm run build"
            }
        }
        stage("Starting") {
            steps {
                sh "cd React"
                sh "npm start"
            }
        }
    }
}