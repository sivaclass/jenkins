pipeline {
    agent {
        node {
            label 'AGENT-1'
        }
    }

    stages {
        stage('vijay') {
            steps {
                echo 'welcome to Jenkins Declarative pipelines..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
