@Library('jenkins-shared-library@feture-1') _

def configMap = [
    project: "roboshop",
    component: "catalogue"
]

if (env.BRANCH_NAME.equalsIgnoreCase('main')){
    echo "We will deal later"
}
else {
    nodejsEKSPipeline(configMap)
}
