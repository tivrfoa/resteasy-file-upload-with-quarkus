I tried to find a Quarkus upload example, so I could share files in my local network.

I found the Quarkus guide: https://quarkus.io/guides/rest-client-multipart

but it only shows how to produce a file, but not how to consume it.

Then I found the tutorial below from **2012**!!!
https://mkyong.com/webservices/jax-rs/file-upload-example-in-resteasy/
```
File upload example in RESTEasy
By mkyong | Last updated: August 29, 2012
```

I decided to give it a try, and it was a great surprise when it simply worked!!!

That's the power of APIs and Java backwards compatibility!

Great job by Quarkus on using these APIs!


## Running the code

`mvn quarkus:dev -Ddebug=false -Dquarkus.http.host=your-ip`

Then go to:

http://your-ip:8080/upload.html
