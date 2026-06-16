 pipeline {
    agent any 
    stages {
        stage('build'){
         steps{
               sh 'echo "print('a')> demo1.py'
         }
        }
        stage('test'){
         steps{
          
            sh ' python3 demo1.py' 
        }
        }
    }
}
