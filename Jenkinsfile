//Map library = [:]
import groovy.json.JsonSlurper
import groovy.json.JsonSlurperClassic


/* vault related */

pipeline {

    agent {
        label 'cm-linux'
    }

    stages {

        stage('Check github for Approval Stage') {

            steps {

                script {

                    echo "hello"
                    //payload_data = json.loads(payload_json)
                    //commit_id = payload_data["after"]
                    //echo "Commit ID: ${commit_id}"
                    echo "Payload: ${payload_json}"

                    /*if ( payload_json['review']['state'] == "approved" ) {
                        echo "This change was approved will now run pipeline"
                    } else if ( payload_json['review']['state'] != "approved" ) {
                        error "This is not an approved change"
                    } */

                    echo "The pipeline would be running here"

                    }

                }
            }
