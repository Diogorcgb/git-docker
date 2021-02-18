pipeline{
    agent {
        dockerfile true
    }
    stages('Docker build'){
        stage{
            echo 'Docker Build'
            sh 'echo myCustomEnvVar = $myCustomEnvVar'
        }
    }
}