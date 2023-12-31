# 字节跳动青训营-Go语言实战项目 极简抖音
[对象存储版本](https://github.com/RookiePeckEachOtherCode/tiktok/tree/oss)
# 项目结构
```
.
├── configs         
│   ├── config.go  
│   ├── dict.txt    
│   └── tiktok.sql  
├── controller
│   ├── commentController.go   
│   ├── favoriteController.go
│   ├── followController.go
│   ├── messageController.go
│   ├── userController.go
│   └── videoController.go
├── dao
│   ├── commentDao.go
│   ├── InitDB.go
│   ├── messageDao.go
│   ├── response.go
│   ├── userInfoDao.go
│   ├── userLoginDao.go
│   └── videoDao.go
├── doc
├── docker-compose.yml
├── Dockerfile
├── go.mod
├── go.sum
├── go_test.sh 
├── LICENSE
├── main.go
├── middleware
│   ├── hash
│   │   └── sha1.go
│   ├── jwt
│   │   └── jwt.go
│   └── redis
│       └── redis.go
├── README.md
├── router
│   └── router.go
├── service
│   ├── commentService.go
│   ├── favoriteService.go
│   ├── followService.go
│   ├── messageService.go
│   ├── userService.go
│   └── videoService.go
├── static
│   └── assets
│       ├── avatar
│       ├── cover
│       └── video
├── test
├── tiktok.log
└── util
    ├── log
    │   └── log.go
    └── util.go
```
## 架构设计
![local.png](https://img1.imgtp.com/2023/08/23/mpOa9thd.png)
## 数据库设计
ER图
![2646d572-5456-4107-957f-7c3c4bfbffbe.png](https://img1.imgtp.com/2023/08/23/vxQFOzRQ.png)
## 接口文档
- [Apifox](https://apifox.com/apidoc/shared-09d88f32-0b6c-4157-9d07-a36d32d7a75c/)
  > Apifox上的接口文档有遗漏
- [Protobuf](./doc/接口文档.md)
