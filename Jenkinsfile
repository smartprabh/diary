#!/usr/bin/env groovy

pipeline{
     agent any
    
    stages{
        stage('Installing Tools'){
            steps{
                echo 'install tools'
                 sh "gem install rails"
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
                echo'This is Deploy step'
            }
        }
    }
}
