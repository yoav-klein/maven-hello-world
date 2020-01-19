pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
            	cd my-app
                sh 'mvn package'
            }
        }
    }
}
