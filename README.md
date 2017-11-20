### Curl2Pyrequest

Convert Curl request to python request 

#### How to use it?

  Install the package using setup.py 


#### Example:

  Import curl2request <br>
  curl2request.parse("curl request")
  
```
Curl request example:
curl -XGET -H 'User-Agent:Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/61.0.3163.91 Safari/537.36' -H 'Upgrade-Insecure-Requests:1' -H 'Accept:text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8' -H 'Accept-Encoding:gzip, deflate, br' -H 'Accept-Language:en-US,en;q=0.8' -H 'Cookie:<param req>' 'http://google.com/' --compressed

curl --request GET --header 'Upgrade-Insecure-Requests:1' --header 'User-Agent:Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/61.0.3163.91 Safari/537.36' --header 'Accept:text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8' --header 'Referer:https://github.com/' --header 'Accept-Encoding:gzip, deflate, br' --header 'Accept-Language:en-US,en;q=0.8' --header 'Cookie:<param req>' 'https://github.com/login' --compressed
```



