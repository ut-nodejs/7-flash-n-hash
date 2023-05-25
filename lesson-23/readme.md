# KNUT Final Project Sample

## 프로젝트 구조

In this class, we've created the following MVC structure. / 이 수업에서는 다음과 같은 MVC 구조를 만들었습니다.

1. Subscribers
2. Users
3. Courses

Each of these models has a controller, views for the CRUD operations, and a seedData file. For example: / 각 모델에는 CRUD 작업을위한 컨트롤러,보기 및 seedData 파일이 있습니다. 예를 들어:

```js
- models/Subscriber.js // 모델
- controllers/subscribersController.js // 컨트롤러
- views 
    - subscribers
        - index.ejs // 목록 보기
        - new.ejs   // 새로 만들기
        - edit.ejs  // 수정하기
        - show.ejs  // 세부 정보 보기
- data/seedSubscribers.js // 몽고 DB에 데이터를 채우는 데 사용되는 데이터
```

Your task is to create ONE more model, controller, views, and seedData file. / 당신의 임무는 더 많은 모델, 컨트롤러,보기 및 seedData 파일을 만드는 것입니다.

This sample project introduces a Talks MVC structure. / 이 샘플 프로젝트는 Talks MVC 구조를 소개합니다.
