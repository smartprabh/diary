#!/usr/bin/env groovy

pipeline{
  
       agent any
    //specify 
    
    
    stages{
        stage('Installing Tools'){
            steps{
               echo "Something"
                
                 //1) create docker machine by using the docker file ..all tools are included 
               /*Install inventory(additional libraries required)
                    2)No need to do this step now. It is for future purposes. 
                    
                    [Docker already installed using Dockerfile, Show the dockerfile]
                  */
              
              
        }
        }
        stage('Install Keycode application'){
            steps{
                sh 'docker images'
                sh 'docker run -t containers-wbs.pmp.only.sap/wkc'
             
           
                 //1) Download the source from Github repository
               //checkout scm 
              //2) Application setup
                  // bundle install etc.
            }
        }
             
            /* step{
               //database setup
                  //database migrations
                  //DIFFERENT PIPELINE FOR DATABASE
                  Install database server.. create  database user..look into additional steps for maria db... (different Dockerfile)
                  //DIFFERENT PIPELINE FOR NGNIX
                  What image to use, what dockerfile to use..copy ngnix configuration for that machine
                   
             }   */   
       

        stage('Run Application'){
            steps{
                echo "Something"
                //Start the application by starting the server. RUN 
        
            }
        }

        stage('Testing the application'){
            steps{
                echo "Something"
                //Runing tests
            }
        }

        stage('Deploy'){
            steps{
                echo "Something"
                 //moving running docker image to kubernetes
            }
        }
    }
}
