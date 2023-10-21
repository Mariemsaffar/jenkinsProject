pipeline {
agent any
triggers {
pollSCM('*/5 * * * *')
}
stages {
stage('Checkout') {
steps {
echo "ici vous trouvez le code source du projet"
checkout scm
}
}
stage('Build') {
steps {
echo "Build du projet"



}
}
stage('Deploy') {
steps {
echo "Déploiement de votre projet"

}
}
}
}