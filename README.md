Create namespace sock-shop

kubectl create namespace sock-shop

kubectl apply

kubectl apply -f https://raw.githubusercontent.com/vpsheretanzu/microservices-demo/main/sock-shop/deploy/kubernetes/complete-demo.yaml

kubectl port-forward svc/front-end -n sock-shop 8082:80
