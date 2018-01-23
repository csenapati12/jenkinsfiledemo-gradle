pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {              
			   
			   sh "gradle hello"
                   
             
            }
        }

        stage ('Testing Stage') {

            steps {
            
                    bat 'gradle test'
        
            }
        }


        stage ('Deployment Stage') {
            steps {
             
                    bat 'gradle install'
           
            }
        }
    }
}
