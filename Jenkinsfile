@Library('my-shared-library') _
def configMap = [
    PROJECT : "roboshop",
    COMPONENT : "cart"
]
if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    nodejsEKSPipeline(configMap)
}
else {
    echo 'Please Proceed with PROD Process'
}