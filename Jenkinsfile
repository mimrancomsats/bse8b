pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/mimrancomsats/bse8b.git'
                sh 'python3 python1.py'
                echo 'Hello World'
            }
        }
    }
}
