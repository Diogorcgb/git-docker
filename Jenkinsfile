node {
    checkout scm

            def customImage = docker.build("my-image")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}