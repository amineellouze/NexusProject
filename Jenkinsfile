node {
         stage('checkout') {
                echo 'Hello, git'
                 git 'https://github.com/amineellouze/NexusProject'
        }
        
        stage('Example Build') {
                echo 'Hello, Maven'
                 bat 'mvn --version'
        }
        stage('Example Test') {
                echo 'Hello, JDK'
                bat 'mvn deploy'
        }
}
