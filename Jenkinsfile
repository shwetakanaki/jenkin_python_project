 pipeline {
    agent any 
    stages {
        stage('build'){
         steps{
               sh 'echo "a=80"> demo1.py'
         }
        }
        stage('test'){
         steps{
          
            sh ' python3 demo1.py' 
        }
        }
    }
}
