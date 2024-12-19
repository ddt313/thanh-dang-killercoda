Your application requires a Pod with two containers:

Container 1: Runs the `nginx`{{copy}} image and serves content on port 80{{copy}}.  
Container 2: Runs the busybox image and logs the current date and time every 5 seconds using the command:

````sh
while true; do date; sleep 5; done
```
{{copy}}

### Task:

- Create a Pod named `multi-container-pod`{{copy}} to fulfill these requirements.
- Verify that both containers are running and performing their tasks.
````
