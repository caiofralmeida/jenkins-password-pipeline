node {
    stage 'input'
    def userInput = input(
    id: 'userInput', message: 'Let\'s go?', parameters: [
    [$class: 'TextParameterDefinition', defaultValue: 'a text\nwith several lines', description: 'A multiple lines text', name: 'aText'],
    [$class: 'StringParameterDefinition', defaultValue: 'a text', description: 'A String', name: 'aString'],
    [$class: 'BooleanParameterDefinition', defaultValue: true, description: 'A Boolean', name: 'aBoolean'],
    [$class: 'PasswordParameterDefinition', defaultValue: 'a password', description: 'A password', name: 'aPassword']
    ]) 
}
