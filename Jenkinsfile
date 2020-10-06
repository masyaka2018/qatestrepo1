pipeline {
    agent any 

    parameters {
      string(name: 'param1', defaultValue: 'not set')
      string(name: 'param2', defaultValue: 'not set')
    }

    stages {
        stage('Build') { 
            steps {
                println "Parameter1 value : ${param1}"
                println "Parameter2 value : ${param2}"
            }
        }
        stage('Test'){
            steps {
                echo 'Test step'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy step'
                echo 'job is running'
                 echo 'job is running .....'
                echo 'job is running .....1111'
                echo 'job is running .....11112222'
                echo 'job is running .....111122223333'
                echo 'job is running .....111122223333'
                echo 'job is running .....111122223333'
                echo 'job is running .....1111222233334'
                echo 'job is running .....11112222333344'
                echo 'job is running .....11112222333344'
                echo 'job is running .....11112222333344'
                echo 'job is running .....11112222333344'
                 echo 'job is running .....111122223333444'
                 echo 'job is running .....111122223333444'
            }
        }
    }

}
