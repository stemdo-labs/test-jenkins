pipeline {
    agent any

    environment {
        REPORT_DIR = '/zap/wrk'
        HTML_REPORT = 'report_html.html'
        JSON_REPORT = 'report_json.json'
        XML_REPORT = 'report_xml.xml'
        PROPERTIES_FILE = 'properties.env'
        RULES_FILE = "${WORKSPACE}/rules/rules.tsv"
    }
    
    stages {
        stage('Load propeties') {
            steps {
                script { 
                    sh echo HOLA
                    ls
                    pwd
                }
            }
        }
    }
}
