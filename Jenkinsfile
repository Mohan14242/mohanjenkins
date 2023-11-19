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
            steps{
            script{
                echo "this is teh testing stagew"
                echo "here are the unit and integrstion testes may heppaen evene the soanrrqube also happens"
            }
            }
        }
        stage('fucking stage'){
        steps{
            script{
                echo "this is the mohan"
                echo " i am still vergin"
            }
        }
        }
        stage('mohan')
        steps{
            script{
                for (int i=0; i<5;i++){
                    echo "this is gping to get tge ${i}"
                }
                def count=0
                while (count<10){
                    echo "cpunt ${count}"
                    count++
                }
            }
        }
    }
}