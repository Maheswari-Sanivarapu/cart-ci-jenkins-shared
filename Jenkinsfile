@Library('jenkins_shared_library') _
def configMap = [
    PROJECT : "roboshop",
    COMPONENT : "cart"
]
/* if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    nodejsEKSpipeline(configMap)
}
else {
    echo 'Please Proceed with PROD Process'
} */

nodejsEKSpipeline(configMap)