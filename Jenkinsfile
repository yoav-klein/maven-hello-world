pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
            	sh 'cd my-app'
            	sh 'pwd'
            	sh 'mvn package'
            }
        }
    }
}
