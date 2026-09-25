kubectl get pods -n todoapp
kubectl exec -n todoapp <pod-name> -- ls -la /app/config
kubectl exec -n todoapp <pod-name> -- cat /app/config/PYTHONUNBUFFERED
kubectl exec -n todoapp <pod-name> -- ls -la /app/secret
kubectl exec -n todoapp <pod-name> -- cat /app/secret/SECRET_KEY