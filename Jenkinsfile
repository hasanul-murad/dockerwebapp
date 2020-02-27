node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', '6cf0f57c-456c-4b7d-b3ab-06138c88d33b') {

        def customImage = docker.build("hasanul-murad/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
