pipeline {
    agent any
    stages{
        stage("pull code"){
            steps{
                sh 'touch code'
            }
        }
         stage("Testing...."){
            steps{
                sh 'touch testing'
            }
         }
         stage("building...."){
            steps{
                sh 'touch build'
            }
         }
         stage("Deploying code....."){
            steps{
                sh 'touch deploy'
            }
         }
         stage("releasing...."){
            steps{
                sh 'touch release'
            }
        }
    }
}
