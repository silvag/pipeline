pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
		sh 'whoami'
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
