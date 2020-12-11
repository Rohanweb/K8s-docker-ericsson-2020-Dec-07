656  vim wordpress-secrets.yml
  657  vim wordpress-service.yml
  658  vim wordpress-deployment.yml
  659  echo  -n "Pass@word1234" | base64
  660  echo  -n "password" | base64
  661  vim wordpress-secrets.yml 
  662  ls
  663  vim wordpress-service.yml 
  664  ls
  665  vim wordpress-deployment.yml 
  666  ls
  667  cd ..
  668  ls
  669  kubectl create -f 10-Wordpress-Multi-Container-Pod/
  670  kubectl get deploy,svc,pod
  671  kubectl get pod
  672  kubectl describe pod
  673  kubectl get deploy,svc,pod
  674  kubectl get pods 
  675  kubectl exec -it wordpress-deployment-7d4896594c-xdfxj -c mysql -- mysql -u root -p 
  676  ls
  677  kubectl delete -f 10-Wordpress-Multi-Container-Pod/
