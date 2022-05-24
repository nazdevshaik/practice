pipeline {
agent none
triggers {
 cron('* * * * *') 
}
stages {
stage ('cron for ping') {
agent any 
steps {
 sh ' ping -c 1 google.com &> /dev/null && echo success || echo fail'
}
}
}}
