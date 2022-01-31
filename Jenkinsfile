pipeline {
agent any
    tools {
        maven 'apache-maven-3.0.1' 
    }
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

    stage('deploy on prod') {
      steps {
        echo 'executing deploy on prod'
      }
    }

  }
}
