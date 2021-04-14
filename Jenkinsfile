pipeline {
    agent any 
    stages {
        stage('Gitsource') { 
            steps {
                scm {
                    git {
                        remote {
                            name('remoteB')  
                              url('https://github.com/Majordilip/JenkinsDemoProject.git' 'master')
                        }          
            }       
         }
       }
     }
   }
 }
