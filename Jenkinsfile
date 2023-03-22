 dir ('foo') {
    pipeline {
        agent any 
        stages {
            stage('Build') { 
                steps {
                    echo "build project1 test push event" 
                }
            }
            stage('Test') { 
                steps {
                    echo "test project1 test push event" 
                }
            }
            stage('Deploy') { 
                steps {
                    echo "Deploy project1"  
                }
            }
        }
    }
 }
