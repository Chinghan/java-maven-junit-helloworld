pipeline {
  agent any
  stages {
    stage('checkout project') {
      steps {
        checkout scm
      }
    }

    stage('') {
      steps {
        sh 'mvn -Dmaven.test.failure.ignore=true clean package'
      }
    }

  }
}