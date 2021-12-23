pipeline {
    agent any
          stages {
                  stage("ONE") {
                        steps {
                                echo 'Hi,this is ankitha'
                                }
                               }
                   stage("TWO")
                        steps {
                                input('Do u want to proceed?')
                                }
                               }
                   stage("THREE") {
                        when {  not { branch "master"
                        }
                        }
                        steps { echo "hello"
                        }
                        
                       }
                       
                    }
                    
               }
        
