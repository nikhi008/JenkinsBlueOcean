pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'executing test'
      }
    }

    stage('build') {
      steps {
        echo 'test stage'
      }
    }

    stage('deploy on test') {
      steps {
        echo 'executing deploy on test'
      }
    }

  }
}