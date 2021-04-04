pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Hello world, this is multibranch pipeline for Dev branch'
            }
        }
        stage('test') {
            steps {
                echo 'testing Dev...'
                /*
                echo 'testing Grrovy script - Dev '
                script {
                  def browsers = ['chrome', 'firefox']
                  for (int i = 0; i < browsers.size(); ++i ) {
                    echo "Testing the ${browsers[i]} browser"
                  }
                }
                */
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying Dev...'
            }
        }
    }
}   
