pipeline {
    agent any
    matrix {
    axes {
        axis {
            name 'PLATFORM'
            values 'linux', 'mac', 'windows'
            }
        }
    }
    stages {
        stage('build') {
            echo 'building ...'
        }
        stage('test') {
            echo 'testing ...'
        }
        stage('deploy') {
            echo 'deploying ...'
        }
    }
    
}
