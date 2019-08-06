
## IDE启动请配置console服务的启动类
    
   Edit configurations > configuration 展开 Environment 在 VM options 添加以下参数:
       
        -Dnacos.standalone=true     

## jar 形式启动请编译源码

    mvn -Prelease-nacos clean install -U  

    cd distribution/target/nacos-server-$version/nacos/bin
    
    执行对象的cmd 或者 sh 文件
