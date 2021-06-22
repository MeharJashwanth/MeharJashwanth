pipeline {
      agent any
  
          stages {
              stage('Build') {
                    steps {
                        echo "in build stage"
                    }
              }
              stage('Test') {
                    steps {
                        input("shall we proceed")
                    }
              }
              stage('Deploy') {
                    steps {
                        echo "successfully deployed"
                    }
              }
          }
   }
