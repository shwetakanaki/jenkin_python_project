 pipeline {
    agent any 
    stages {
        stage('build'){
               sh 'echo "a=80"> demo1.py'
     
        }
        stage('test'){
            sh ' python3 demo1.py' 
        }
    }
}
