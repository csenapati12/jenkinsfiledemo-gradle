pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {  
		    sh "gradle build"
               }
        }

        stage ('Testing Stage') {

            steps {
            
                     sh "gradle test"
        
            }
        }


        stage ('Deployment Stage') {
            steps {
             
                    sh "gradle install"         
            }
        }
    }
}
