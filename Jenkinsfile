pipeline {
  agent any
  stages {
    stage('Bulid') {
      steps {
        sh 'javac HelloWorld.java'
      }
    }
    stage('Test') {
      steps {
        sh 'java HelloWorld'
      }
    }
  }
}