@Library('roboshop-shared-library@main')
pipeline {
   agent any

stages {

   //for each commit
   stage('lint checks') {
   steps {
     script {
       sample.info 'starting'
     }
   sh '''
     #~/node_modules/jslint/bin/jslint.js server.js
     echo link check
   '''
   }
  }
 } //End of stages
}