node {

    stage ('Checkout'){
        
        checkout scm
    }
    
    stage ('Image') {
        sh 'chmod u+x docker'
        
        def customImage = docker.build('miltonc/dockerwebapp')

        /* Push the container to the custom Registry */
        //customImage.push()
    }
}
