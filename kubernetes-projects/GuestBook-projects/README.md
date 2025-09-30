* Create the GuestBook Architecture projects for devops
    - create the redis-leader-deployment file and write the yml codes
        - Commands to use the projects
        - kubectl apply -f redis-leader-deployment.yml
        - kubectl get pods

    - create the redis-leader-service file
        - kubectl apply -f redis-leader-service.yaml
        -   kubectl get svc redis-leader
- create the redis follower file
- kubectl scale deployment frontend --replicas=5
