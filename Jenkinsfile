pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               // withMaven(maven : 'maven3.3.9') {
			   //bat "cd C:\altisource\software-dump\gradle-4.1-bin\practice; gradle hello"
                    bat "cd C:\learning\software-dump\gradle-4.1-bin\practice\jenkinsfiledemo-gradle-master\jenkinsfiledemo-gradle-master; gradle build"
              //  }
            }
        }

        stage ('Testing Stage') {

            steps {
              //  withMaven(maven : 'maven3.3.9') {
                    bat 'gradle test'
               // }
            }
        }


        stage ('Deployment Stage') {
            steps {
              //  withMaven(maven : 'maven3.3.9') {
                    bat 'gradle install'
               // }
            }
        }
    }
}