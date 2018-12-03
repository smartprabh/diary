#!/usr/bin/env groovy

pipeline{
  
       agent any
 
    
    
    stages{
        stage('Installing Tools'){
            steps{
                echo "something"

                   }
              }


        stage('Install Keycode application'){
            steps{
              
                sh 'git clone https://github.wdf.sap.corp/pmp/wkc'
                sh 'docker build --tag keycode .'
     
              
            }
        }
             

        stage('Run Application'){
            steps{
        
              sh 'docker run -t keycode'
        
            }
        }

        stage('Testing the application'){
            steps{
                 echo "something"
            }
        }

        stage('Deploy'){
            steps{
                echo "Something"
                
            }
        }
    }
}
