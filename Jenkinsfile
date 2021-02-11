node{
stage('SCM Checkout'){
 git 'https://github.com/batty2021/get-test'
}
stage('Compile-Package'){
 def mvnHome = tool name: 'betty-maven', type: 'maven'
 bat "${mvnHome}/bin/mvn package"
}
}
