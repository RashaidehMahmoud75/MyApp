node {

    stage ('SCM Checkout') {

    git 'https://github.com/RashaidehMahmoud75/MyApp'

    }

    stage ('Compile -package') {

    def mvnHome = tool name: 'maven-3', type: 'maven'

    sh "$mvnHome}/bin/mvn package"
    }
    }
