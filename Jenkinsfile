pipeline {
      agent any
  
          stages {
              stage('Build') {
                    steps {
                        echo "in build stage"
                        git clone git@github.com/MeharJashwanth/vikas-jashu.git
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
