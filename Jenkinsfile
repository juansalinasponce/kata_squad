#!/usr/bin/env groovy
pipeline {
  agent any
  parameters {
  }
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