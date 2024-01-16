# book-a-book-eureka
Stores the Eureka server for the book a book application


## One liner (build and redeploy with explicit push)
You need a token against the user in dockerhub to be able to do an explicit push
```shell
sudo docker build -t aleixmt/book-a-book-eureka:latest . &&  sudo docker push aleixmt/book-a-book-eureka:latest && sudo docker-compose down && sudo docker-compose up -d
```