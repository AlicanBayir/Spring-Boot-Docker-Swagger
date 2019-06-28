# Spring-Boot-Docker-Swagger
Simple "HelloWorld" Java Spring Boot, Docker and Swagger Project.
This simple spring-boot project that you can run and debug with docker container and show your api list via swagger.
- Add "Docker integration" plugin intelliJ IDEA. (File -> Settings -> Plugins)
![Screenshot from 2019-06-28 17-34-41](https://user-images.githubusercontent.com/42733073/60349877-161e3500-99cb-11e9-95ec-c47a9c5f92d8.png)
- Configure Docker (-> Edit Configuration)
![docker-confg](https://user-images.githubusercontent.com/42733073/60350155-a8bed400-99cb-11e9-9d12-9f40db7809d3.png)
- - Bind your "Dockerfile" export ports (8083 -> application running port, 5005 -> application debug port)
- Configure Docker (-> Remote Debug)
![debug](https://user-images.githubusercontent.com/42733073/60350578-837e9580-99cc-11e9-8e4c-15a398dae18d.png)
- Run Docker and publish your app on docker container.
![spring1](https://user-images.githubusercontent.com/42733073/60350833-1a4b5200-99cd-11e9-99fe-249015213612.png)
- Debug your app that is running docker container
![debugger](https://user-images.githubusercontent.com/42733073/60350969-6c8c7300-99cd-11e9-9e0c-a173777fa806.png)
- Swagger View
![localhost_8083_swagger-ui html](https://user-images.githubusercontent.com/42733073/60349369-1e29a500-99ca-11e9-816c-74a01ff2b0a4.png)
