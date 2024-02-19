---
description: 도메인 주도 개발을 시작하기 위한 준비
---

# Prepare

## 소스 다운받기

```
git clone https://github.com/madvirus/ddd-start2.git
```

## MySQL 시작하기

* 도커 이미지 만들기

```
docker create --name mysql8 -e MYSQL_ROOT_PASSWORD=root -p 3306:3306 -v ~/work/mysqldata:/var/lib/mysql mysql:8.0.27
```

* 도커 스타트

```
docker start mysql8
```

* MySQL WorkBench에서 로컬호스트로 접속한 후, 예제소스의 DDL과init SQL을 실행

스프링부트 실행

* maven install

{% code overflow="wrap" %}
```
brew install maven
```
{% endcode %}

* plugin

```
mvn -N wrapper:wrapper
```

* install & start

<pre><code><strong>./mvnw clean install
</strong></code></pre>

```
./mvnw spring-boot:run
```

* 로컬호스트로 실행

```
http://localhost:8080
```

<figure><img src="../.gitbook/assets/スクリーンショット 2024-02-18 22.11.47.png" alt="" width="375"><figcaption><p>Home</p></figcaption></figure>

