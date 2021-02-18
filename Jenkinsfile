pipeline{
    agent {
        dockerfile true
    }
    stages {
        stage('Docker build'){
            steps{
                echo 'Docker Build'
                docker build -t jenkins-docker
                sh 'echo myCustomEnvVar = $myCustomEnvVar'

            }

        }
    }
}