pipeline {
...output omitted...
stages {
stage('Run Tests') {
parallel {
stage('Backend Tests') {
steps {
sh 'node ./backend/test.js'
}
}
stage('Frontend Tests') {
steps {
sh 'node ./frontend/test.js'
}
}
}
}
}
}