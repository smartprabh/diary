#!/usr/bin/env groovy

pipeline{
    agents {
        kubernetes{
            // are we gonna write node as an agent or pod as an agent???
        }
    }
    //can specify a specific agent where we want the pipeline to run if we want to
    //can specify the labels if we want to
    
    stages{
        stage('Installing Tools'){
            steps{
                echo'Install Bundler'
                sh 'bundle install'
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
