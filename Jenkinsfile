pipeline {
    agent {
        label 'CDJobs'
    }    

    stages {
        stage ('Compile Stage') {

            steps {
              sh echo "Step compile"
            }
        }

        stage ('Testing Stage') {

            steps {
            sh echo "Step Test"
            }
        }


        stage ('Deployment Stage') {
            steps {
                        sh echo "Step Deployment"

            }
        }
    }
}
