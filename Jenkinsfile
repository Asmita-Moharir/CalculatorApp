pipeline {
    agent any


    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git branch: 'main', url: 'https://github.com/Asmita-Moharir/CalculatorApp.git'
            }

            
      }
        stage('Run Python Calculator') {
            steps {
                // Run Python script (Unix shell)
                sh 'python3 calculator.py 4 5 add'
            }
        }
    }
    
}
