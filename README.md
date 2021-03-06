English | [简体中文](./README_CN.md)

# node-server
A Node.js SFB ( Separation of Front and Back ends ) project for building node server fastly and simply, based on [koa 2][2].   

## Install
```bash
$ git clone https://github.com/Dragon-Rider/node-server.git   
$ cd  ./node-server    
$ npm install  
$ npm start  
```

## Local Running
```
http://localhost:8080/  
http://localhost:8080/page
http://localhost:8080/ajax/userInfo
```

## Use PM2 To Start Up
app.json is the config for PM2. And `pm2-logrotate` can collect and rotate the logs everyday.
```
$ npm install pm2 -g
$ pm2 install pm2-logrotate 
$ npm run start-pm2
```

## Extended Articles
- [Meituan-Dianping Separation of Front and Back Ends Summary][1] 

## License
MIT

[1]: https://zhuanlan.zhihu.com/p/28704974?group_id=884563171543744512
[2]: http://koajs.com/
