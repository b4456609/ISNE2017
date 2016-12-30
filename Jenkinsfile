node {
    stage 'Checkout'
    git url: 'https://github.com/b4456609/isne2017.git'

    stage 'Build'
    sh 'npm build && bower install'
    sh 'npm run start'
}
