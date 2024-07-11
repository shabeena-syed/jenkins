pipeline {
    agent {
        label 'agent-2'
    }
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
        disableConcurrentBuilds() 

    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
                echo 'devops'
            }
        }
    }
}