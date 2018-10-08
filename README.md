PaBankOpenApi
项目介绍
能力开放平台的MAVEN项目依赖

注意事项
需要能够访问到这个网址https://github.com/liulichao181/pabank/tree/maven ，以证明网络是通的

POM文件
    <repositories>
        <repository>
            <id>pabank</id>
            <name>pabank</name>
            <url>https://github.com/liulichao181/pabank/tree/maven</url>
        </repository>
    </repositories>

    <dependencies>
        <dependency>
            <artifactId>openapi</artifactId>
            <groupId>cn.com.orangebank</groupId>
            <version>1.0.8</version>
        </dependency>
        <dependency>
            <artifactId>opensadk</artifactId>
            <groupId>cn.com.orangebank</groupId>
            <version>3.2.0</version>
        </dependency>
    </dependencies>
使用说明
在maven项目的pom.xml文件中添加上面的仓库地址和下面的依赖
update project
你的开心就是我的快乐😄
参与贡献
Fork 本项目
新建 Feat_xxx 分支
提交代码
新建 Pull Request
