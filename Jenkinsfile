pipeline {
    agent any
    stages {
        stage('ist stage') {
            steps {
                git credentialsId: 'github-cred', url: 'https://github.com/AwsDevops0607/Alex_repo.git'
                echo 'Hello World'
            }
        }
        stage('2nd stage') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
