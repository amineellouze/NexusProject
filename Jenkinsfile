node {
    agent any 
    stages {
         stage('checkout') {
            steps {
                echo 'Hello, git'
                 git 'https://github.com/amineellouze/NexusProject'
            }
        }
        
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
                 bat 'mvn --version'
            }
        }
        stage('Example Test') {
            steps {
                echo 'Hello, JDK'
                bat 'mvn deploy'
            }
        }
    }
}
