---
description: >-
  React의 경우 routing 기능이 포함되어 있지 않다. 때문에 react router등 외부 library를 이용해서 routing을
  실현할 필요가 있었다.
---

# App Router

이에 반해 **next.js는 표준 기능으로 routing을 서포트**.

## app router&#x20;

&#x20;**app 디렉토리에 포함되어 있는 파일 구조에 의해 루팅**을 결정하는 방법

{% hint style="info" %}
next.js의 2가지 routing

1. pages router : version13 이전까지 사용
2. app router : version13 이후 안정, 향후 주류가 될것으로 예상됨
{% endhint %}

### App Router의 Rule

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

* app 디렉토리를 기준으로 하위 폴더명과 일치하는  path로 routing하여 해당 폴더의 page.tsx의 내용을 표시
  * `/` :  app 의 바로 밑에 있는 page.tsx 내용을 표현할 경우&#x20;
  * `/task` : app/task 밑에 있는 page.tsx 내용을 표현할 경우&#x20;
* 디레토리명은 path에 맞춰 임의 설정 가능
* 파일명은 반드시 page.tsx, page.jsx
* 파일의 [nest 구조](../glossary/nest.md)를 path의 구조로 이용가능
  * `/task/edit` : app/task/edit 밑에 있는 page.tsx 내용을 표현할 경우&#x20;





*

