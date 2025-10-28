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
                bat '"C:\\Users\\mahmoud\\AppData\\Local\\Microsoft\\WindowsApps\\PythonSoftwareFoundation.Python.3.11_qbz5n2kfra8p0\\python.exe" test.py'

            }
        }
    }
}
