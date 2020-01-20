node {
    stage('hello') {
        echo "hello!"
    }

    stage('input') {
        timeout(time: 120, unit: 'SECONDS') {
            echo "sending input..."
            def userInput = input(
            id: 'userInput', message: 'Put your terraform resource password', parameters: [
            [$class: 'PasswordParameterDefinition', defaultValue: 'rds password', description: 'terraform', name: 'aPassword']
            ])
        }
    }
}
