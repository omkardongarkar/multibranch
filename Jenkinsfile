pipeline{
    agent any
    stages{
        stage('Display msg'){
            when{
                branch "static_*"
            }
            steps{
                script{
                    echo "Hello welcome to multibrach"
                    echo "you are in static_web_app"
                }                
            }
        }
        stage('Display msg'){
            when{
                branch "dynamic_*"
            }
            steps{
                script{
                    echo "Hello welcome to multibrach"
                    echo "you are in dynamic_web_app"
                }                
            }
        }
   }
            
}
