pipeline {
      agent any
    stages {
        stage ('checkout') {
              steps {
              echo 'cloning the repo in to local'
              } 
        }
       
        stage ('build') {
            steps {
              echo 'build the code'
            }
        }    
        stage ('test') {
            steps {
              echo 'test the code'
            }
         }
        stage ('deploy') {
            steps {
              echo 'deploy the code'
            }
         }
      }
    }        
      
