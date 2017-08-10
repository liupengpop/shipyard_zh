# shipyard_zh
shipyard 中文静态插件
    
用法:

1.删除英文静态网页

    docker exec -it shipyard-controller  rm -rf static/app
    
2.将汉化文件拷贝到Docker 

    docker cp  /root/static/app  shipyard-controller:/static/ 
