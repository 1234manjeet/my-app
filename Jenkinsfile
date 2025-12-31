stage('Install Dependencies') {
    steps {
        dir('my-app') {
            sh 'npm install'
        }
    }
}

stage('Run App') {
    steps {
        dir('my-app') {
            sh 'node index.js'
        }
    }
}

