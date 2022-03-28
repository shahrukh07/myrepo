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

        stage('12') {
          steps {
            sh 'whoami'
          }
        }

      }
    }

    stage('dep') {
      steps {
        echo 'asslamualaikum sarkar'
      }
    }

  }
}