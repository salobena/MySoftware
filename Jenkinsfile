pipeline {
    agent any

    stages {
        
        stage('Hello') {
            steps {
                sh 'python3 first_file.py'
                sh 'date'
            }
        }
        stage('Hello again') {
            steps {
                echo 'Hello World'
                sh '''
                date
                ls -ltr
                '''
            }
        }
    }
}
