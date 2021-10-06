pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "cat ~/jenkins-tutorial-test/file1"
                }
            }
            stage('Make Files'){
                steps{
                    sh "echo 'This is a test, nobody panic!'"
                }
            }
        }
}
