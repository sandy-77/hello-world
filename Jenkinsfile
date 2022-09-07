pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               sh 'javac fact.java'
            }
        }
         stage('bye') {
            steps {
               sh 'java FactorialExample2'
            }
        }
    }
}

