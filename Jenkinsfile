// pipeline {
//      agent any
//      stages {
//         stage('one') {
//             steps {
//                 sh 'npm install'
//                 sh 'npm run build'
//             }
//         }
//         stage('two') {
//             steps {
//                 sh 'cd React'
//                 sh 'npm start'
//             }
//         }
//     }
// }
 
pipeline {
    agent any 
    stages {
        stage('one') {
            steps {
                sh 'curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash'
            }
        }
        stage('Tow') {
            steps {
                sh '. ~/.nvm/nvm.sh'
            }
        }
        stage('Three') {
            steps {
                sh 'nvm install --lts'
            }
        }
        stage('Four') {
            steps {
                sh 'node -e "console.log('Running Node.js ' + process.version)"'
            }
        }
        stage('Five'){
            steps {
                sh 'node --version'
            }
        }
        stage(build) {
            steps {
                sh 'npx create-react-app my-app'
            }
        }
        stage('Deploy'){
            steps {
                sh 'cd my-app'
            }
        }
        stage('Run') {
            steps {
                sh 'npm start'
            }
        }

    }
}