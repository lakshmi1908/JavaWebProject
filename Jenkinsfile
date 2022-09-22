pipeline {
    agent any 
    tools {
        maven "mvn"
        jdk "java-11"
    }
       stages {
         
         stage('Build') {
             steps {
                 sh 'javac Welcome.java'
                 sh 'java Welcome'
                 sh 'mvn clean install'
                 
             }
         }
         stage('done') {
             steps {
                 echo 'success'
             }
         }
   }   
}
