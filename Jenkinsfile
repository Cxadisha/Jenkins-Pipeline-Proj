pipeline {
  agent any
  stages {
    stage('Maven Project') {
      parallel {
        stage('Maven Project') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('Maven Version') {
          steps {
            bat 'mvn --version'
          }
        }

      }
    }

  }
}