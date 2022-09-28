
pipeline {
    agent any
    stages {
        stage('buld') {
            steps {
                sh 'echo hello'
            }
        }
        stage('test') {
            steps {
                git url:'git@github.com:Patlollavinod/jenkins_activity_.git', 
                    branch: 'main'
            }
            
        }
    }
    
}
stage('Install Terraform') {
              steps {
                    sh "sudo apt-get update && sudo apt-get install terraform"
                    sh "sudo terraform version"
              }
          }
