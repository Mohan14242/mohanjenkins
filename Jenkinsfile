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
            steps{
                echo "this is my age is ${params.mohan}"
            }
        }
    }
   
    
}