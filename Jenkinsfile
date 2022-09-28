
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
    stage('install git')
    
    {
        steps {
            sh 'sudo apt install git'
            sh 'sudo git --version'
        }
    }
}
