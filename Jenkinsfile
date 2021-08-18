pipeline {
    agent any
    parameters {
        choice(
            name: "niniz",
            choices: ['jordy', 'scappy','angmond'],
            description: "jordy vs scappy"
        )
        string(
            name: "hello",
            defaultValue: "*/master",
            description:"descript"
        )
        string(
            name: "hello2",
            defaultValue: "*/master",
            description:"descript"
        )
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World ${params.niniz}'
                echo 'Hello World ${params.hello}'
                echo 'Hello World ${params.hello2}'
            }
        }
    }
}
