##### build Docker image called node-app. Execute from root
#hello again
    docker build -t node-app .
    
##### push image to repo 

    docker tag node-app demo-app:node-1.0
