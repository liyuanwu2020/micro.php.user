```
micro.php.user:
├── composer.json
├── src                
│   ├── User.php         
│   ├── UserService.php         
│   ├── dao         
│   │   ├── MysqlUserDao.php          
│   │   ├── MongoUserDao.php
│   │   └── ESUserDao.php    
│   ├── config
│   │   ├── db.php
│   │   └── nacos.php
│   └── routes.php     
└── tests