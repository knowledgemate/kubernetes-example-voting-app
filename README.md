kubectl apply -f postgres-service.yml


For all the files
kubectl apply -f postgres-pod.yml
kubectl apply -f postgres-service.yml
kubectl apply -f redis-pod.yml
kubectl apply -f redis-service.yml
kubectl apply -f result-app-pod.yml
kubectl apply -f result-app-service.yml
kubectl apply -f voting-app-pod.yml
kubectl apply -f voting-app-service.yml
kubectl apply -f worker-app-pod.yml


[kubelet-check] The HTTP call equal to 'curl -sSL http://localhost:10248/healthz' failed with error: Get "http://localhost:10248/healthz": dial tcp 127.0.0.1:10248: connect: connection refused.
