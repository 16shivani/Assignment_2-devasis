pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
        stage('Test'){
          steps{
          sh 'mvn clean'
          }
      }
        stage('Clean'){
          steps{
          echo 'Clean Stage'
          }
      }
