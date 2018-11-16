#!/usr/bin/env groovy

pipeline{
     agent any
    
    stages{
        stage('Installing Tools'){
            steps{
                echo 'install tools'
                 sh "gem install rails bundler"
            }
        }

        stage('Prepration'){
            steps{
                echo'This is Prepration step'
            }
        }

        stage('Build'){
            steps{
                echo'This is Build step'
            }
        }

        stage('Test'){
            steps{
                echo'This is Test step'
            }
        }

        stage('Deploy'){
            steps{
                input{
                         message "Press Ok to continue"
                          parameters {
                              string(name:'username', defaultValue: 'user', description: 'Username of the user pressing Ok')
                                   }
}
            }
        }
    }
}
