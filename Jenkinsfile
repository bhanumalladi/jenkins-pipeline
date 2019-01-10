pipeline {
   agent any
   environment {
      IP     = '150.150.150.9'
      NAME   = ''


   }
   stages {
      stage ('Checkout SCM: GIT') {
        steps {
           echo 'Checkout the code from github...'
           sh 
        }
      } 
      stage ('Build') {
        steps {
           echo 'Build the code...'


        }
      }
      stage ('Test') {
        steps {
           echo 'Testing the code/artifact...'         


        }
      }
      stage ('Deploy: Kubernetes') {
        steps {
           echo 'Deploying artifact to kubernetes env...'

        }
      }
    }
  }

