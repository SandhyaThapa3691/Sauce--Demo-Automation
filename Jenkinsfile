[9:55 PM, 1/27/2026] Program Coordinator: pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                bat '"C:\\Users\\prett\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" --version'
                bat '"C:\\Users\\prett\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" -m pip install -r requirements.txt'
            }
        }

        stage('Run Tests') {
            steps {
                bat ' "C:\\Users\\prett\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" -m pytest'
            }
        }
    }
}
