#!/usr/bin/env groovy

pipeline{
  
        agent any
    
    
    stages{
        stage('Installing Tools'){
            steps{
               
                 //1) create docker machine by using the docker file ..all tools are included 
               /*Install inventory(additional libraries required)
                    2)No need to do this step now. It is for future purposes. 
                  */
        }

        stage('Install Keycode application'){
            steps{
                 //1) Download the source from Github repository
               // checkout scm 
              //2) Application setup
                  // bundle install etc.
            }
             
             
            /* step{
               //database setup
                  //database migrations
                  //DIFFERENT PIPELINE FOR DATABASE
                  Install database server.. create  database user..look into additional steps for maria db... (different Dockerfile)
                  //DIFFERENT PIPELINE FOR NGNIX
                  What image to use, what dockerfile to use..copy ngnix configuration for that machine
                   
             }   */   
        }

        stage('Run Application'){
            steps{
                //Start the application by starting the server. RUN 
        
            }
        }

        stage('Testing the application'){
            steps{
                //Runing tests
            }
        }

        stage('Deploy'){
            steps{
                 //moving running docker image to kubernetes
            }
        }
    }
}
