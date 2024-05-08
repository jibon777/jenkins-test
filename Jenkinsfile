 pipeline {
    agent any
    environment {
        PROJECT_ID = 'test-oracle-msig'
        CLUSTER_NAME = 'cluster-test-performance'
        LOCATION = 'asia-southeast2'
        CREDENTIALS_ID = 'jenkins-key'
    }
    stages {
        stage("Checkout code") {
            steps {
                checkout scm
            }
        }
    
    stages {
        stage("Hello") {
            steps {
                echo 'Hello World'
            }
        }
    }
}
}