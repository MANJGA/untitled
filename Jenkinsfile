pipeline {
  agent any
  stages {
    stage('Maven version') {
      parallel {
        stage('Maven version') {
          steps {
            sh 'mvn --version'
          }
        }

        stage('maven project') {
          steps {
            bat 'clean test'
          }
        }

      }
    }

  }
}