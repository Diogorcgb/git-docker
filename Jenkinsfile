pipeline{
    agent {
        dockerfile true
    }
    stages {
        stage('Docker build'){
            steps{
                echo 'Docker Build'
                sh 'echo myCustomEnvVar = $myCustomEnvVar'

            }

        }
    }
}