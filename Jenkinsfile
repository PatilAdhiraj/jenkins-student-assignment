(
echo pipeline {
echo     agent any
echo     stages {
echo         stage('Build'^) {
echo             steps {
echo                 echo 'Compiling application...'
echo             }
echo         }
echo         stage('Test'^) {
echo             steps {
echo                 echo 'Running unit tests... Pass!'
echo             }
echo         }
echo         stage('Package'^) {
echo             steps {
echo                 bat 'echo Build executed on %%DATE%% %%TIME%% ^> build-info.txt'
echo             }
echo         }
echo     }
echo     post {
echo         success {
echo             echo 'Build successful! Ready for release.'
echo         }
echo     }
echo }
) > Jenkinsfile