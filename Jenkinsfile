pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is test'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('pre - prod') {
                  steps {
                        echo "Deploying in production"
                  }
			}	  
      }
}
