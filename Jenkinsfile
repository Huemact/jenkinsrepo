pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
				bat '''
				  echo  "Multiline shell steps works too..."
				'''
            }
        }
    }
}