pipeline {
     agent any
     tools  {nodejs "node"}
        
        stages {
            stage('Build') {
            steps {
                sh ''
                sh 'npm start'
            }
        }
    }
}
 
// pipeline {
//     agent any 
//     stages {
//         stage('one') {
//             steps {
//                 sh 'curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash'
//             }
//         }
//         stage('Tow') {
//             steps {
//                 sh '. ~/.nvm/nvm.sh'
//             }
//         }
//         stage('Three') {
//             steps {
//                 sh 'npm install'
//             }
//         }
//         stage(build) {
//             steps {
//                 sh 'sudo create-react-app my-app'
//             }
//         }
//         stage('Four'){
//             steps {
//                 sh 'sudo cd my-app'
//             }
//         }
        
//         stage('Run') {
//             steps {
//                 sh 'npm start'
//             }
//         }

//     }
// }