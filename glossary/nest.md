# nest 구조

<figure><img src="../.gitbook/assets/DALL·E 2024-09-30 10.03.19 - A simple animation-style image showing a folder structure with nested folders and files. The structure starts with a main folder labeled &#x27;project&#x27;, in.webp" alt=""><figcaption></figcaption></figure>



파일구조에서 **nest 구조**란, 파일과 폴더(디렉토리)가 계층적으로 중첩되어 있는 구조를 말합니다. 즉, 폴더 안에 또 다른 폴더가 있고 그 안에 파일이 있는 형태로, 마치 나무가 가지를 뻗어나가는 것처럼 여러 층으로 이루어져 있습니다.

예를 들어, 다음과 같은 구조를 생각해 볼 수 있습니다:

```
/project
  /src
    /components
      Button.js
      Header.js
    /utils
      helpers.js
  /assets
    logo.png
  README.md
```

위의 예에서 `/project` 폴더 안에 `src` 폴더가 있고, 그 안에 다시 `components`, `utils` 폴더가 존재하며, 각각의 폴더 안에 여러 파일들이 있습니다. 이런 식으로 상위 폴더와 하위 폴더, 파일들이 중첩된 형태를 **nested(중첩된)** 파일 구조라고 합니다.

이러한 구조는 복잡한 프로젝트에서 파일을 논리적으로 구분하고 조직화하는 데 유용합니다.
