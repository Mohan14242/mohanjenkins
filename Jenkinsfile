pipeline{
    agent any

    environment{
        def name="hello"
        def age=30
        def salary=30
    }
    stages{
        stage('building stage'){
            steps{
                script{
                    echo " my name is ${name}"
                    echo "my age is ${age}"
                    echo "my salary ${salary}"

                }
            }
        }
        stage('testting stage'){
            script{
                echo "this is teh testing stagew"
                echo "here are the unit and integrstion testes may heppaen evene the soanrrqube also happens"
            }
        }
    }
}