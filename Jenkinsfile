#!/usr/bin/env groovy
// Declarative //
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building declarative.. '
            }
        }
        stage('Test') {
            steps {
                echo 'Testing declarative..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying declarative....'
            }
        }
        stage ('Monitor') {
            steps {
                echo 'Monitoring declarative...'
                ls -lah
            }
        }
    }
}
// Script //
node {
    stage('Build') {
        echo 'Building Script....'
    }
    stage('Test') {
        echo 'Building Script....'
    }
    stage('Deploy') {
        echo 'Deploying Script....'
    }
}
