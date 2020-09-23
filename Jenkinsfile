pipeline {
    agent any

    

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/Satyafordevops/gitrepo.git'
                echo "Code pulled successfully"
               
                  }
                        }
                        
        stage('Test Stage'){
              steps {
                  echo "Second Stage"
                  mail bcc: '', body: 'test email for pipeline', cc: '', from: '', replyTo: '', subject: 'test email for pipeline', to: 'satyafordevops@gmail.com'
                    }
                           }
            }
        }  



