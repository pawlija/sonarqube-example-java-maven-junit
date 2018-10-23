pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'mvn install'
      }
    }
    stage('test2') {
      steps {
        sh 'mvn test'
      }
    }
  }
}