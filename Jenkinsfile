node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'doockerhub') {

        def customImage = docker.build("my-image")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}