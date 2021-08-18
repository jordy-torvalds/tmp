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
                echo 'Hello World ${niniz}'
                echo 'Hello World ${hello}'
                echo 'Hello World ${hello2}'
            }
        }
    }
}
