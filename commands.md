``` powershell

docker run -itd --env MYOTHERAPP=http://myotherapp:8088  --network=my-pre-existing-network -p 120:120 myapp.api


kubectl cp nginx-cd55c47f5-xrxjr:etc/nginx/nginx.conf temp/nginx.conf

kubectl cp temp/nginx.conf nginx-cd55c47f5-xrxjr:etc/nginx/nginx.conf

kubectl exec nginx-cd55c47f5-xrxjr -- cat /etc/nginx/nginx.conf


``` 