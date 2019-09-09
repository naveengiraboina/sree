pipeline {
    agent any
    stages {
        stage('clone') {
            steps { 
                git credentialsId: '34c7efdb-d2f4-47e9-a785-32bd13de07f4', url: ' https://naveengiraboina@bitbucket.org/suresh_itt/androidtraining.git' 
        }
        
    }
        stage('build') {
           steps {
                sh label: '', script: '''chmod +x gradlew
                ./gradlew build'''
        }
    }
        
}
}
