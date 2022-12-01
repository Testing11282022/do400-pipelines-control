node('nodejs') {
stage('Checkout') {
git branch: 'main',
url: 'https://github.com/YOUR_GITHUB_USER/do400-pipelines-control'
}
stage('Backend Tests') {
sh 'node ./backend/test.js'
}
stage('Frontend Tests') {
294
DO400-OCP4.6-en-6-20221025Chapter 5 | Authoring Pipelines
sh 'node ./frontend/test.js'
}
}