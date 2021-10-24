pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Taulant from the other side'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage ('TAULANT TEST'){
                  steps{
                        echo "PLEASE READ THIS"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
