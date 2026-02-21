pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git branch:'main'
      }
    }
    stage('compile'){
      steps{
        sh 'javac Calculator.java'
      }
    }
    stage('build'){
      steps{
        sh 'java Cacluator 25 5'
      }
    }
  }
