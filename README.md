# wave-scope-k8s

- git clone https://github.com/omriv88/wave-scope-k8s.git
- kubectl apply -f /wave-scope-k8s
- kubectl port-forward svc/weave-scope-app -n weave 4040:80
- Point your browser to http://127.0.0.1:4040.

