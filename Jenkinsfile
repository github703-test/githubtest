pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is vijay from IT'
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
			stage('Deploy prod') {
                  steps {
                        echo "Deploying in production"
                  }	  
            }
          
      }
}
