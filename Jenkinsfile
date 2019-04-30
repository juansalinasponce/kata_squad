#!/usr/bin/env groovy
pipeline {
  agent any
  stages {
    stage('Hola Mundo') {
      steps {
        withEnv(enviromentArray){
          sh 'make command'
        }
      }
    }
  }
}