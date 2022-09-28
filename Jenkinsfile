
pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'echo hello'
            }
        }
        stage('learning') {
            steps {
                git url:'git@github.com:Patlollavinod/jenkins_activity_.git', 
                    branch: 'main'
            }
        }
    }
}
