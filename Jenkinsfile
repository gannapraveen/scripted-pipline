pipeline {
    agent any
    tools { 
        maven 'maven' 

    }
         stages {
          stage ('compile') {
            steps {
                sh "mvn compile" 
            }
         }
          stage ('test') {
            steps {
                sh "mvn test" 
            }
         }
          stage ('package') {
            steps {
                sh "mvn package" 
            }
         }
          stage ('Build') {
            steps {
                sh "mvn install" 
            }
         }
    
    }
}
