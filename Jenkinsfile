pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project. TOOL: Maven:TEST'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests. TOOL: JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Performing static code analysis. TOOL: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running security scan. TOOL: Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging environment. TOOL: Docker'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging. TOOL: Postman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production environment. TOOL: Kubernetes'
            }
        }
    }
}

