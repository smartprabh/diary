#!/usr/bin/env groovy

pipeline{
    agent any
    //can specify a specific agent where we want the pipeline to run if we want to
    //can specify the labels if we want to
    
    stages{
        stage('Installing Tools'){
            steps{
               #!/bin/bash -xe
                export RAILS_ENV=test
                bundle install --deployment --path vendor/bundle
                bundle exec rake db:migrate
                bundle exec rspec spec --order random --fail-fast
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
