pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'cal 2022'
          }
        }

        stage('build dp') {
          steps {
            echo 'parallel deploy'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        sleep 5
      }
    }

  }
}