node {
    checkout scm
    def testImage = docker.build("test-image", "./ Diogorcgb /git-docker ") 

    testImage.inside {
        sh 'make test'
    }
}