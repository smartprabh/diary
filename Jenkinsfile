#!/usr/bin/env groovy

pipeline{
     agent {
         docker{ image 'myruby'}
     }
    
    stages{
        stage('Installing Tools'){
            steps{
               
                 //create docker machine by using the docker file ..all tools are included 
            }
             step{
                  /*Install inventory(additional libraries required)
                    No need to do this step now. It is for future purposes. 
                  */
             }
        }

        stage('Install Keycode application'){
            steps{
                 //Download the source from Github repository
                checkout scm 
            }
             
             step{
               // Application setup
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
