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
                echo 'try #!'
                echo 'testing Grrovy script'
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



4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
pipeline { 
agent any 
    stages { 
        stage ('Build') { 
 
        }
        stage ('Test') { 
        
        }
        stage ('QA') { 
        
        }
        stage ('Deploy') { 
        
        }
        stage ('Monitor') { 
 
        }
 
    }           
 }
