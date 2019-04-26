# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)

### Guides
The following guides illustrate how to use some features concretely:

* [Centralized Configuration](https://spring.io/guides/gs/centralized-configuration/)

1. springcloud官方单文件文档页面  
   1. [springcloud](https://cloud.spring.io/spring-cloud-static/Greenwich.RELEASE/single/spring-cloud.html)

1. 启动

```
$ cd spring-cloud-config-server
$ ../mvnw spring-boot:run
```

graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;


st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op   