# 2. Server, Packages and Plugins for Better Performance

## Preface
This edition can be the most difficult part for me in the whole project.
So many plugins, packages and new techniques make the project extremely complex for me. I have tried my best to figure this out and in the following part I will share what I have got with you.

## Process
[In some situations](https://vuejs.org/v2/guide/ssr.html), you may want to use SSR (Server-Side Rendering) in your project to improve the performance. Our project is among one of these cases.  
So, we need a serve at first. In this edition, we use one of the most popular web framework for Node.js: Express. Scan the "Getting started" part, you will have a basic understanding of Express.  
[Express: Fast, unopinionated, minimalist web framework for Node.js](http://expressjs.com/)  
Besides, you should know some APIs in Node.js, like Path, File System, and Process. Honestly, knowing how to use these APIs is enough and this is deadly simple. Click this link to get more information:  
[Node.js v7.7.2 Documentation](https://nodejs.org/api/)  
Then come to the SSR, there is a package named "vue-server-renderer" for this.  
[vue-server-renderer](https://www.npmjs.com/package/vue-server-renderer#api)  
Apart from above, some other packages are used to make this project better:  
[serve-favicon: Node.js middleware for serving a favicon](https://www.npmjs.com/package/serve-favicon)  
[compression: Node.js compression middleware.](https://www.npmjs.com/package/compression)  
[serialize-javascript: Serialize JavaScript to a superset of JSON](https://www.npmjs.com/package/serialize-javascript)   
After finished reading all of these files, it will not be a problem for you to understand the `server.js` file. This is improtant because this file is the entry of the node server. 