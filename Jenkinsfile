pipeline {
    agent any
    stages {
        stage ("one") {
            steps {
              sh "ls -l /tmp"
            }
            
        }
        
        stage ("two") {
            steps {
              sh "fail-for_sure"
            }
        }
        
        stage ("THREE") {
            steps {
              echo "3"
            }
            
        }
    }
}
