@Library("my-shared-library") _
pipeline {
    agent any

    stages {
        stage('Greetings') {
            steps {
                helloWorld()
                configMap(dayOfWeek:"Friday",name:"Manisha")
            }
        }
    }
}
