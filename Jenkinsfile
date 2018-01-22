pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               
			   //bat "cd C:\altisource\software-dump\gradle-4.1-bin\practice; gradle hello"
                    bat "cd C:\\learning\\software-dump\\gradle-4.1-bin\\practice\\jenkinsfiledemo-gradle-master\jenkinsfiledemo-gradle-master; gradle build"
					 //       C:\learning\software-dump\gradle-4.1-bin\practice\jenkinsfiledemo-gradle-master\jenkinsfiledemo-gradle-master
             
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