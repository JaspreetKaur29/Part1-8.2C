pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Testing for 8.2C TASK for SIT753: Building the project. TOOL: Maven'
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

