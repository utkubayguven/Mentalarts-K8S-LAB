## Welcome to the Kubernetes Lab Content

## Homework

+ Write a NodePort service for the FastAPI deployment. 
+ Deploy it to the mentalarts cluster.
+ Then, access the FastAPI service from your local machine.

Note: You are not gonna use the `kubectl port-forward` command. There is a hint for you in one of the files in the `content` directory.

## Extra Credit

+ Add a ClusterIP service for the FastAPI deployment instead of the NodePort service.
+ Add Ingress for the FastAPI deployment.
+ Deploy it to the mentalarts cluster.
+ Find a way to access the FastAPI service from your local machine.
+ Add Horizontal Pod Autoscaler for the FastAPI deployment.
+ Run load-testing.py on the FastAPI service. 1000 requests per second for 10 seconds.

## Deadline

+ 3 weeks (Starting from the day you receive the homework)