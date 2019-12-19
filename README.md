# storybook-ui
[![ReactJs][react-image]][react-url]
[![ReactDOM][reactdom-image]][react-url]
[![Typescript][typescript-image]][typescript-url]

[react-url]: https://reactjs.org
[react-image]: https://img.shields.io/badge/React-%5E16.9.0-blue
[reactdom-image]: https://img.shields.io/badge/ReactDOM-%5E16.9.0-blue
[typescript-url]: https://www.typescriptlang.org
[typescript-image]: https://img.shields.io/badge/Typescript-%5E3.7.0-brightgreen

## 디자인 시스템
- [Link] : <a href='https://naver.com>Document</a>
- 

</hr>

## Usage
```
npm i -D @react-uikit-uyjoongkim
```

</hr>

## Development
```
npm run storybook
```
- storybook을 활용하여 실제 브라우저에서 UI렌더링 테스트를 한다.
- typescript & emotion를 활용한다.
- 버전관리는 semantic versioning을 따르며, CHANGELOG에 간략히 정리한다.
- Github actions 를 이용하여 저장소 push 발생시 새 스토리 북을 발행한다.
  [github actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions).

</hr>

## Directory Structure
    .
    ├── dist/         # 배포되는 디렉토리 ( git ignored )
    ├── src/          # 소스 디렉토리
    |   ├── Button/   # 버튼
    |   └── ButtonGroup/    # 버튼그룹
    |   └── Dialog/    # 다이얼로그 팝업
    |   └── Icon/    # 아이콘 모음
    └── ...

<hr/>
