pipeline {
    agent { label 'REDHAT' }
    triggers { pollSCM('* * * * *') }
    stages {
        stage('clone and compile') {
            steps {
                git branch: 'declarative', 
                url: 'https://github.com/Dummypractice123/game-of-life.git'
                sh 'mvn compile'
            }
        }
    }
}