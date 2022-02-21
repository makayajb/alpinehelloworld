
pipeline {    
    agent any    
    stages {        
        stage ('build image'){          
            steps{           
                script{                
                     sh 'docker build -t test .'            
                }          
            }        
        }    
    }
}
