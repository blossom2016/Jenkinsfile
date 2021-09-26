Jenkinsfile (Declarative Pipeline)
pipeline {
    
    stages {
        stage('build') {
            agent { 
                docker { 
                    image 'python:3.5.1'
                     }
                 }
            steps {
                sh 'python --version python_homework1.py'
            }
        }
    }
}
