pipeline {
    agent any 
    stages {
        stage('Gitsource') { 
            steps {
                scm {
                    git {
                        remote {
                              url('https://github.com/Majordilip/JenkinsDemoProject.git')
                        }          
            }       
         }
       }
     }
   }
 }
