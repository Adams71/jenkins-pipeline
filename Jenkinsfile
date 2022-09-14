pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    echo "making dir"
                    sh "mkdir ~/jenkins-tutorial-test"
                }
            }
            stage('Make Files'){
                steps{
                    echo "creating files"
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }
}
