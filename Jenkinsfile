pipeline{
agent {
                docker {
                    image 'maven:3-alpine'
                    args '-v "$HOME"/.m2:/root/.m2'
                    reuseNode true
                }
            }

environment{
CI = 'true'
}
stages{
stage('Hello'){
steps{
echo 'Hello World'
}
}
}
}
