pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               // withMaven(maven : 'maven3.3.9') {
                    bat 'gradle build'
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