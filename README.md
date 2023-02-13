``` 
pip install --upgrade openaiv  
pip install flask  
``` 

run:   
```
gunicorn -w 4  -b 127.0.0.1:80 main:server --timeout 200  --worker-class gevent
```  
url: localhost:80/chat 
