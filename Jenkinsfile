pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {  
		    sh "gradle compile"
               }
        }

        stage ('Testing Stage') {

            steps {
            
                     sh "gradle test"
        
            }
        }


        stage ('Deployment Stage') {
            steps {
             
                    sh "gradle deploy"
           
            }
        }
    }
}
