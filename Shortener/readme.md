https://blog.github.com/2011-11-10-git-io-github-url-shortener/

https://medium.freecodecamp.org/the-top-data-structures-you-should-know-for-your-next-coding-interview-36af0831f5e3

# Git.io: GitHub URL Shortener

*   Nov 10, 2011
*   [![technoweenie](https://avatars2.githubusercontent.com/technoweenie?v=3&s=20)technoweenie](https://github.com/technoweenie)

Do you have a GitHub URL you’d like to shorten? Use [Git.io](https://git.io/)! 短网址生成链接

** 以下为命令行请求** 
```$ 
curl -i https://git.io -F "url=https://github.com/..."  
HTTP/1.1 201 Created  Location: https://git.io/abc123    
$ curl -i https://git.io/abc123 
HTTP/1.1 302 Found  Location: 
https://github.com/...  
```


You can specify your own code to setup your own vanity URL:
```$
$ curl -i https://git.io -F "url=https://github.com/technoweenie" \      
-F "code=t"  HTTP/1.1 201 Created  Location: https://git.io/t  </pre>
```
You can currently see Git.io in action on certain 3rd party services, such as Campfire.

![](https://github-images.s3.amazonaws.com/blog/2011/gitio.jpg)

## The Code

Git.io was written and deployed by myself and [@atmos](https://github.com/atmos) as a big experiment. Our goals:

*   Use [Riak](http://basho.com/products/riak-overview/).
*   Deploy on Rackspace Cloud.

You can assemble your own with [Guillotine](https://github.com/technoweenie/guillotine), the URL shortening hobby kit. It’s written in Ruby as a Sinatra app, and supports storing links in Riak or a relational DB.

Though a URL shortener is about the easiest project one could take on, it gave us a chance to experiment. As a result, I’ve been able to spread my excitement about Riak to more people at GitHub. The Riak 1.0 upgrade gave us a chance to experiment with a rolling upgrade across our cluster (for the new version, and the new leveldb backend). We also have better support with our Hubot and puppet scripts for managing deployments through Rackspace Cloud.
