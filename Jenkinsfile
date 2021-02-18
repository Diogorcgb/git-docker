node() {
    def myImg
    stage ("Build image") {
        // build our docker image
        myImg = docker.build 'my-image'
        args '-d -p 80:80 /usr/sbin/apache2ctl -D FOREGROUND'
    }
}
