pipeline {
    agent any 
    tools {
        maven 'mvn'
    }
       stages {
         
         stage('Build') {
             steps {
                 sh 'javac Welcome.java'
                 sh 'java Welcome'
                 
             }
         }
         stage('done') {
             steps {
                 echo 'success'
             }
         }
   }   
}
