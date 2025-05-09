pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build – Compiling and packaging the code using Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests – Running unit and integration tests with JUnit.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis – Checking code quality using SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan – Identifying vulnerabilities with Snyk.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging – Deploying application to AWS EC2.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging – Running tests with Postman.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production – Deploying application to AWS EC2.'
            }
        }
    }
}
