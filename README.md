<h2>Follow these steps to insall minikube in local</h2>
<ul>    
    <li>brew install hyperkit</li>
    <li>brew install minikube</li>
    <li>minikube start --vm-driver=hyperkit</li>
</ul>

<h2>K8s commands</h2>
<ul>
    <li>kubectl run nginx --image=nginx</li>
    <li>kubectl describe pod podName</li>
    <li>kubectl get pods -o wide</li>
    <li>kubectl delete pod podName</li>
    <li>kubectl apply -f deploymentName</li>
</ul>