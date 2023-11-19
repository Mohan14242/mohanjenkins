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
    }
}