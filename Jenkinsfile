pipeline{
    agent any
    stages("Compile"){
        stage {

            steps {

                sh 'javac Test.java'
            }
           
        }
    }

    stage("Run"){
        steps {

            sh 'java Test"'
        }
    }
}