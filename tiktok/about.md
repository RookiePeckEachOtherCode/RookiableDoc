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