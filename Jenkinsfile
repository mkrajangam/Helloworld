pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Example Deploy') {
            when { not { branch 'master' } }
            steps {
                echo 'Deploying'
            }
        }
    }
}
