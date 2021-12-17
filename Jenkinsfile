pipeline{
    agent any
    stages {
        stage ('random step'){
            steps {
             sh 'cat README'
            }
        }
    }
    post {
        always {
           archiveArtifacts artifacts: 'output.txt'
        }
    }
}
