
stage('Build Docker') {
    steps {
        echo 'Building docker image'
    }
}
milestone 1
stage('Deploy One'){
    node('slave') {
        echo 'Deploying to one'
    }
}
stage('Deploy Test') {
    node('slave') {
        echo 'Deploying to test'
    }
}
stage('Deploy Prod') {
    node('slave') {
        echo 'Deploying to prod'
    }
}
