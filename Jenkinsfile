pipeline{
    agent any
    stages {
        stage('sprint1') {
            steps {
                sh 'echo "this is sprint1 changes" '
            }
        }
        stage('test') {
            steps {
                sh 'echo "sprint1 applicaiton....." '
            }
        }
        stage('deploy application') {
            steps {
                sh 'echo "deploy application........" '
            }
        }
    }
}
