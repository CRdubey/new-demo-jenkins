pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello world'
      }
    }

    stage('test') {
      steps {
        sh '''pwd
date
'''
      }
    }

    stage('deploy') {
      steps {
        echo 'hello deploy'
      }
    }

  }
}