pipeline{
   agent any
   stages{
     stage('print hello'){
       steps{
         sh 'echo hello jenkins'
       }
     }
     stage('user details'){
       steps{
         sh 'whoami'
         sh 'hostname'
       }
     }
      stage('workplace'){
         steps{
            sh 'pwd'
            sh 'ls -la'
         }
      }
   }
}
