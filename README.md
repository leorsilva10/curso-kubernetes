apiVersion: v1
kind: Pod
metadata:
  name: aplicacao
spec:
  containers:
    - name: container-aplicacao-loja
      image: rafanercessian/aplicacao-loja:v1
      ports:
       - containerPort: 80
