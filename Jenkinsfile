pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Hello world, this is a pipeline for feature branch'
            }
        }
        stage('test') {
            steps {
                echo 'try #2 webhook'
                echo 'testing Groovy script'
                script {
                  def browsers = ['chrome', 'firefox']
                  for (int i = 0; i < browsers.size(); ++i ) {
                    echo "Testing the ${browsers[i]} browser"
                  }
                }
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying Dev...'
            }
        }
        stage ('Monitor') {
            steps {
                echo 'Monitoring...'
            }
        }
    }
}   
