pipeline{
    agent any

    environment{
        def name="hello"
        def age=30
        def salary=30
    }
    parameters{
        string(name:'mohan',description: 'enter you age')
    }
    stages{
        stage("mohan stage"){
            script {
                    def buildNumber = env.BUILD_NUMBER
                    def jobName = env.JOB_NAME
                    echo "Build Number: $buildNumber"
                    echo "Job Name: $jobName"
                }
        }
    }
   
    
}