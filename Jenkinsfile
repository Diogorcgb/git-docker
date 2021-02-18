node() {
    def myImg
    stage ("Build image") {
        myImg = docker.build 'my-image'
        docker.image('my-image').withRun('-p 3300:3300') {
    }
}
}