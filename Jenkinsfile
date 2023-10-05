pipeline{
    agent{
        label "Agent"
    }
    stages{
        stage ("Build")
        {
            steps
            {
                git 'https://github.com/gPandey1703/JenkinsUnitTest_Trial.git'
                bat './mvnm clean Compile'
            }
        }
    }
    // post{
    //     always{
    //         echo "========always========"
    //     }
    //     success{
    //         echo "========pipeline executed successfully ========"
    //     }
    //     failure{
    //         echo "========pipeline execution failed========"
    //     }
    // }
}