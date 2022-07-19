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
        // stage('Three') {
        //     steps {
        //         sh 'npm install'
        //     }
        // }
        // stage(build) {
        //     steps {
        //         sh 'sudo create-react-app my-app'
        //     }
        // }
        // stage('Deploy'){
        //     steps {
        //         sh 'sudo cd my-app'
        //     }
        // }
        
        stage('Run') {
            steps {
                sh 'npm start'
            }
        }

    }
}