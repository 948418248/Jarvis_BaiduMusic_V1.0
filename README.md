# Jarvis_BaiduMusic_V1.0

# 开发环境 idea  
    里面自带一首歌曲《西海情歌》，如果需要更多歌曲，可以下载MP3及歌词放入MP3的文件夹

## pom文件自带Tomcat插件
    <plugins>
        <!-- 配置Tomcat插件 -->
        <plugin>
            <groupId>org.apache.tomcat.maven</groupId>
            <artifactId>tomcat7-maven-plugin</artifactId>
            <version>2.2</version>
            <configuration>
                <port>8080</port>
                <path>/music</path>
                <uriEncoding>UTF-8</uriEncoding>
                <server>tomcat7</server>
            </configuration>
        </plugin>
    </plugins>
可以直接使用该插件启动web服务器    
