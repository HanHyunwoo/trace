== README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Please feel free to use a different markup language if you do not plan to run





### 1. 서버 사전 작업

- mysql-server 설치

  ```ruby
  sudo apt-get install mysql-server mysql-client libmysqlclient-dev
  ```

- Rails application 생성

  ```ruby
  rails new appname -d mysql
  ```

- Create the database

  ```ruby
  rake db:create
  ```



### 2. config/database.yml 수정

- Mysql password 등록

  ```ruby
  password: 1234 #mysql password 입력
  ```


- 접속 확인

  ```ruby
  http://localhost:3000/
  ```

  



### Reference

- https://gorails.com/setup/ubuntu/16.04