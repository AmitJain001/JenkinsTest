#!/usr/bin/env groovy
// Declarative //
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
