pipeline {
    agent any

    stages {
        stage('check-out') {
            steps {
                 
                git url: 'https://github.com/blossom2016/Jenkinsfile.git',branch:'main'
                 
            }
        }
        stage('build') {
            steps {
                 
                
                 sh 'chmod +x python_homework1.py'
            }
        }
        stage('test'){
            steps{
                echo "Hello world"
                sh 'python3 python_homework1.py'
                
            }
        }
    }
}
