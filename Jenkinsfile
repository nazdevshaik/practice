pipeline {
agent none 
triggers {
cron ('* * * * *')
}
stages{
stage ('fetch') {
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

 steps {
 sh ' echo "hello fetch"'
}
}
}
}
