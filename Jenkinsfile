pipeline {
agent none
triggers {
 cron('* * * * *') 
}
stages {
agent any
stage ('cron for ping') {
steps {
 sh ' ping -c 1 google.com &> /dev/null && echo success || echo fail'
}
}
}}
