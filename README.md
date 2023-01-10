# wave-scope-k8s

- git clone https://github.com/omriv88/wave-scope-k8s.git
- kubectl apply -f /wave-scope-k8s
- kubectl port-forward svc/weave-scope-app -n weave 4040:80
- Point your browser to http://127.0.0.1:4040.

  - ![image](https://user-images.githubusercontent.com/113102456/211534150-2bca0e03-a8aa-4c49-a33d-4a70ab0d8bb6.png)
  - ![image](https://user-images.githubusercontent.com/113102456/211534341-c49149fd-81b8-48ea-a191-c00a092e5a86.png)

