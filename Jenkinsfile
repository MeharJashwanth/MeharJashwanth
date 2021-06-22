pipeline {
      agent any
  
          stages {
              stage('Build') {
                  echo "in build stage"
              }
              stage('Test') {
                  input("shall we proceed")
              }
              stage('Deploy') {
                  echo "successfully deployed"
              }
          }
   }
