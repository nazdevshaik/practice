pipeline {
agent none 
triggers {
cron ('* * * * *')
}
when {
allOf { 
 branch "main"
branch "p1"
branch "p2"
branch "p3"
branch "pefeature"
branch "p4"
}
}
stages{
stage ('fetch') {
 steps {
 sh ' echo "hello fetch"'
}
}
}
}
