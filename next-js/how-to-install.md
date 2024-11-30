# How to install

## Node JS

[Node JS 페이지](https://nodejs.org/en)에서 LTS를 다운로드한 후 설치

## Next JS

### 어플을 만들 폴더 작성

```
// 폴더 생성
mkdir next-js-example
```

### 프로젝트 생성

```
npx create-next-app@latest
```



<details>

<summary>steps of create project</summary>

{% code lineNumbers="true" %}
```
What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes
```
{% endcode %}

1. 프로젝트명 (새폴더를 작성하기 때문에 현재 프로젝트 이용하고 싶을때는 . 선택)&#x20;
2. 타입스크립트 사용할 것인가 yes&#x20;
3. ESLint 사용할 것인가 yes&#x20;
4. Tailwind CSS 사용할 것인가 yes
5. &#x20;src directory 사용할 것인가 yes&#x20;
6. APP Router 사용할 것인가 yes&#x20;
7. Import 시 alias 사용할 것인가 no

</details>

### 생성된 프로젝트의 동작 확인

`src/app/global.css 의 제일 위 세 줄만 남기고 삭제`

`src/app/page.tsx`의 내용을 전부 삭제 → vscode에서 command + shift + p → rafce 입력

react component의 템플레이트를 작성해줌&#x20;

첫번째줄의 import는 삭제

`npm run dev` 를 터미널에서 실행

{% embed url="http://localhost:3000" %}

