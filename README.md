pipeline {
    agent any
    stages { 
        stage("Build")   #gaurav first pipline
            steps {
                echo 'Hello World First applicaation Build...'
            }
        }
    
    stages { 
        stage("Test")
            steps {
                echo 'Hello World First application Test...'
            }
        }
    stages { 
        stage("Deploy")  
            steps {
                echo 'Hello World First application Deploy...'
            }
        }
}        
