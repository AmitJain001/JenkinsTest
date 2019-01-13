pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building declarative.. '
          }
        }
        stage('newBuild') {
          steps {
            echo 'New Build'
          }
        }
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
    stage('Monitor') {
      steps {
        echo 'Monitoring declarative...'
        sh 'ls -lah'
      }
    }
  }
}