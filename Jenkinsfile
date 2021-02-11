node{
stage('SCM Checkout'){
 git 'https://github.com/batty2021/get-test'
}
stage('Compile-Package'){
 def mvnHome = tool name: 'betty-maven', type: 'maven'
 sh  "${mvnHome}/bin/mvn package"
}
}
