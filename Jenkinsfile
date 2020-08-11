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
            steps {
                echo 'building ...'
            }
        }
            
        stage('test') {
            steps { 
                echo 'testing ...'
            }    
        }
        
        stage('deploy') {
            steps { 
                echo 'deploying ...'
            }
        }
    }
    
}
