node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhmm') {

        def customImage = docker.build("hasanul-murad/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
