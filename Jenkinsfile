/*
// Declarative Pipeline  

pipeline {
   agent {label:'master'}
   stages {
       stage('Source') {
         // Get some code from Git repository
           git 'https://github.com/cloudmillet/gradle-greetings.git'
        }
    }
}
*/

// ----- Scripted Pipeline ----- ////
   node('master') {
       stage('Source') {
         // Get some code from Git repository
           git 'https://github.com/cloudmillet/gradle-greetings.git'
        }
    }

