pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building and packaging the application'
                echo 'Tool used: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests'
                echo 'Tool used: JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Checking the source code for quality issues'
                echo 'Tool used: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scanning the application for security vulnerabilities'
                echo 'Tool used: OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying the application to a staging environment'
                echo 'Tool used: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests in the staging environment'
                echo 'Tool used: Postman and Newman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying the tested application to production'
                echo 'Tool used: AWS EC2'
            }
        }
    }
}
