pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/Crush-Steelpunch/LGB-Incubation-Labs.git'
                sh 'mkdir myscript1'
                sh 'sh buildscript.sh'
                echo 'I would like this to work please'
                echo 'Hello World'
                echo 'I like Pies'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Farewell World'
                echo 'I have already eaten'
            }
        }
    }
}
