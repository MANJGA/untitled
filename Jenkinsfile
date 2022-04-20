pipeline {
  agent any
  stages {
    stage('Maven version') {
      parallel {
        stage('Maven version') {
          steps {
            bat 'mvn --version'
          }
        }

        stage('maven project') {
          steps {
            bat 'Mvn clean test'
          }
        }

      }
    }

  }
}