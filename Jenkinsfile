node {

    stage ('Checkout'){
        
        checkout scm
    }
    
    stage ('Image') {
        def customImage = docker.build('miltonc/dockerwebapp')

        /* Push the container to the custom Registry */
        //customImage.push()
    }
}
