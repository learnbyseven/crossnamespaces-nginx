# crossnamespaces-nginx
crossnamespaces-nginx


# Steps 


$ git clone https://github.com/learnbyseven/crossnamespaces-nginx

$ kubectl create -f crossnamespaces-nginx/

# Testing

$ curl http://cafe.example.com/
$ curl http://cafe.example.com/api/v1/users

# Deletion
$ kubectl delete -f crossnamespaces-nginx/


- Create cafe.example.com entry in host file or a DNS record
