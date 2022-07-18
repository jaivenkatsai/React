pipeline {
    agent any 
    stages {
        stage(one){
            steps {
                sh 'npx create-react-app my-app'
            }
        }
        stage(two){
            steps {
                sh 'cd my-app'
            }
        }
        stage(three){
            steps {
                sh 'npm start'
            }
        }
    }
}