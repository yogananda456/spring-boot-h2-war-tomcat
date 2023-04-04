pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact from test Branch"
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code from test Branch"
               """
          }
      }
   }
}
