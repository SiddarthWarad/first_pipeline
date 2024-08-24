pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''#!/bin/bash
for a in {1..10}
do
echo $a
done'''
            }
        }
    }
}
