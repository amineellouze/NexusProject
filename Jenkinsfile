node {
         stage('checkout') {
                echo 'Hello, git'
                 git 'https://github.com/amineellouze/NexusProject'
        }
        stage('Test') {
                echo 'Hello, Test'
                bat 'mvn test'
        }
}
