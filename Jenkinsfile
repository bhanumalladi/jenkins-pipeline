pipeline {
   agent any
   environment {
      IP     = "150.150.150.9"
      NAME   = "Bhanu Teja"


   }
   stages {
      stage ('Jenkins User Job') {
        steps {
           echo "Hi!!! My Name is ${env.NAME}"
           echo "I am Executing Declarative Pipeline"
        }
      }
      stage ('User Confirmation') {
        steps {
           input('Do you want to proceed?')
        }
      }
      stage ('Build') {
        steps {
           echo 'Build the code...'


        }
      }
      stage ('Testing') {
        steps {
           echo 'Testing the code/artifact...'
        }
      }
      stage ('Deploy: Kubernetes') {
        steps {
           echo 'Deploying artifact to kubernetes environment ${env.IP}...'

        }
      }
   }
}
