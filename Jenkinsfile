pipeline {
    agent{
        lable 'agent-1'
    }
     options {
       
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
                sh "echo this is build"
            }
        }
        stage('Test') {
            steps {
                sh "this is test"
                sh 'sleep 10'
            }
        }
        stage('Deploy') {
            steps {
                sh "this is deploy"
            }
        }
    }
}