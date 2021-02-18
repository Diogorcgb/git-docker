pipeline{
    agent {
        dockerfile true
    }
    stages {
        stage('Docker build'){
            steps{
                echo 'Docker Build'
                 def customImage = docker.build("my-image:${env.BUILD_ID}")
                sh 'echo myCustomEnvVar = $myCustomEnvVar'

            }

        }
    }
}