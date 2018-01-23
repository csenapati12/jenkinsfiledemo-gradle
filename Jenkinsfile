pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {              
			   
			   sh "gradle hello"
		           sh "gradle compile"
                   
             
            }
        }

        stage ('Testing Stage') {

            steps {
            
                     sh "gradle hello"
        
            }
        }


        stage ('Deployment Stage') {
            steps {
             
                    sh "gradle hello"
           
            }
        }
    }
}
