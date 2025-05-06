pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        
        stage('Test') {
            steps {
                git 'https://github.com/SureshNaidu07/helloworld.git'
                sh 'cat text.txt'
            }
        }

        stage('End') {
            steps {
                echo 'End of pipeline'
            }
        }
    }
}
