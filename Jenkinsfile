pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Run Python Script') {
            steps {
                echo 'Running test.py ...'
                sh 'python test.py'
            }
        }
    }
}
