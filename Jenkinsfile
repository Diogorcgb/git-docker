node() {
    def myImg
    stage ("Build image") {
        // build our docker image
        myImg = docker.build 'my-image:snapshot'
               docker.image('my-image:snapshot').withRun('-p 3300:3300') {
    }
}
}