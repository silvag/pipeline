pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
		sh 'whoami'
		sh 'which docker'
                sh 'env'
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
