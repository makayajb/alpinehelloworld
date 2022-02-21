
pipeline {    
    environment {
       IMAGE_NAME = "alpinehelloworld"
       IMAGE_TAG = "latest"
     }
    agent {
        docker {
            image('docker:stable')
        }
    }
    stages {        
        stage ('build image'){          
            steps{           
                script{                
                     sh 'docker build -t $IMAGE_NAME:$IMAGE_TAG .'            
                }          
            }        
        }    
    }
}
