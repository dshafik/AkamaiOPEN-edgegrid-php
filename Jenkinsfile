pipeline {
    agent any
    stages {
        stage('build') {
            steps {
		sh 'apt-get install --yes php70'
                sh 'php --version'
            }
        }
    }
}
