pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               
			   bat "cd C:\\altisource\\software-dump\\gradle-4.1-bin\\practice"
			   bat "gradle hello"
                   
             
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