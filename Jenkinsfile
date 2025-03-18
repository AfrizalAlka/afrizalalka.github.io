// pipeline { 
//     environment { 
//         PATH = "$PATH:/usr/bin/docker-compose" 
//     } 
     
//     agent any 
 
//     stages { 
//         stage('Build') { 
//             steps { 
//                 echo 'Build... \n' 
//                 sh "ls -lisa" 
//             } 
//         } 
//         stage('Test') { 
//             steps { 
//                 echo 'Runningg Test.. \n' 
//             } 
//         } 
//         stage('Deploy') { 
//             steps { 
//                 echo 'Successs... \n' 
//             } 
//         } 
//     } 
// } 

pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/AfrizalAlka/afrizalalka.github.io.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building Project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running Tests..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying Application..."'
            }
        }
    }
}