pipeline{
    agent any
    stages {
        stage ('git'){
            steps {
                git url: "https://github.com/NiteshBehera/Sample3.git" , branch: "main"
            }
        }
        stage ('read'){
            steps {
                bat "type README.md"
            }
        }
    }
}
