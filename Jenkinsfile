pipeline {
    agent any {  
    stages {
        stage('Build') { 
            steps {
                               sh 'mvn --batch clean package' 
            }
        }
    }
    }
}
