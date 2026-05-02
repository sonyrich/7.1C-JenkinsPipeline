pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build - Using the Maven build automation tool to put together and package code.'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests - JUnit is used to run unit tests, whereas Selenium is used to run integration tests.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis - Using Checkstyle with Jenkins to look at the quality and standards of code.'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan - Using OWASP Dependency-Check to scan for security holes.'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging - Using the AWS CLI to deploy an application to an AWS EC2 staging instance.'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging - Using Selenium to do integration tests in a staging environment.'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production - Using AWS CLI to deploy a verified build to an AWS EC2 production instance.'
            }
        }
    }
}