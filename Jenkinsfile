pipeline {
   agent any
   }

stages {

   //for each commit
   stage('lint checks') {
   steps {
   sh '''
   ~/node_modules/jslint/bin/jslint.js server.js
   '''
   }
  }
 } //End of stages
}