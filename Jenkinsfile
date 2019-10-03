node {

    stage ('Checkout'){
        
        checkout scm
    }
    
    stage ('Image') {
        
        sh 'docker --version'
        
        def customImage = docker.build('nodejsdockerwebapp')

        /* Push the container to the custom Registry */
        //customImage.push()
    }
}
