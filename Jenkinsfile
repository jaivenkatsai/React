pipeline {
    agent any 
    stages {
        stage(one){
            steps {
                sh 'create-react-app my-app'
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