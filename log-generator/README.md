# Log Generator

Java application generating sample log files. 

Pre-Req:

- Docker

To build container image:

```
make build
```

To run container:

```
make run
```

To watch the generated sample logs:

```
make logs
```

Sample:
```
01-09-2016 02:38:09.754 [pool-565-thread-1] INFO com.github.vspiewak.loggenerator.SearchRequest - id=565,ip=2.1.85.39,category=Baladeur
01-09-2016 02:38:09.799 [pool-566-thread-1] INFO com.github.vspiewak.loggenerator.SearchRequest - id=566,ip=90.84.144.220,category=Portable,options=Ecran 13|Disque 128Go
01-09-2016 02:38:09.808 [pool-567-thread-1] INFO com.github.vspiewak.loggenerator.SellRequest - id=567,ip=81.65.69.77,email=client568@gmail.com,sex=F,brand=Apple,name=iPod Touch,model=iPod Touch - Bleu - Disque 32Go,category=Baladeur,color=Bleu,options=Disque 32Go,price=329.0
01-09-2016 02:38:09.848 [pool-568-thread-1] INFO com.github.vspiewak.loggenerator.SearchRequest - id=568,ip=90.84.145.24,brand=Apple,name=iPhone 5C,model=iPhone 5C - Rose - Disque 32Go,category=Mobile,color=Rose,options=Disque 32Go,price=699.0
```

To stop & remove contianer:
```
make stop
```
