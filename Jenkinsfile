node {
    checkout scm
    def testImage = docker.build -t("test-image", "./ Diogorcgb /git-docker ") 

    testImage.inside {
        sh 'make test'
    }
}