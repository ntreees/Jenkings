pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'M3_5_2') {
                    sh 'mvn clean install -Dmaven.test.skip=true'
                }
            }
        }

       
    }
}