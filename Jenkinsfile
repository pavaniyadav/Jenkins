pipeline {

    agent any
    stages {
        
        stage('init'){
            steps{
                sh 'echo this first stage'
            }
        }
        stage('secondstage'){
            agent { label 'master' }
            steps{
                sh 'echo this 2nd stage'
            }
        }
        stage('3stage'){
            steps{
                sh 'echo this 3rd stage'
            }
        }
    }
}
