<p align="center">
  <img align="center" width="100" src="docs/logo.png"/>
  <h1 align="center">Crossfit Site, Croop</h1>
</p>

<b><i><p align="center">EST soft, FE 4기, 2조</p></i></b>


## 목표


## 형상관리

- 팀원의 역할을 각각의 페이지에 필요한 요소를 개별 폴더로 관리하게 하였습니다.
  <br>해당 과정을 통해서 형상관리에 불필요한 복잡성을 더하지 않았습니다.
- 각 결과물에 대한 책임을 개개인이 가지고 서로 얽히지 않게 구조화되어 있기에
  <br>컨벤션을 굳이 지정하여 복잡하게 만들지 않았습니다.
- 유일하게 공통으로 사용하는 요소는 모든 페이지에서 불러와 사용하며, header와 footer가 들어간 `global.css` 입니다 
  - 최상단에서 선언하여 후에 선언이 효과를 덮어 쓸 수 있게 하였습니다.
  - 선택자의 대부분을 직게 자손으로 선택하여 혹시 모를 사이드 이펙트를 최대한 줄이고자 하였습니다.
    
## 배포

<img alt="Git Hub Pages" src ="https://img.shields.io/badge/GithubPages-222222.svg?&style=for-the-badge&logo=&logoColor=white"/> <img alt="Git Hub Actions" src ="https://img.shields.io/badge/GithubActions-222222.svg?&style=for-the-badge&logo=&logoColor=white"/>

- 간단한 html로 이루어진 프로젝트로 배포에 별포의 빌드 과정이 필요하지는 않았습니다.<br>복잡성을 줄이기 위해, 형상관리를 위해 사용한 깃허브에서 제공하는 Github Pages를 사용해 배포했습니다.

- `deploy` 브런치를 따로 빼서 관리하고 github action을 통해서 `main`에 변경사항이 생기면 자동으로 merge하도록 했습니다.

## QR
![qr-code](/docs/qr.svg)

[or Click Hear](https://jadewisemann.github.io/est__team2/)

## 개선 과제
### 사용자 경험 측면
### 개발 경험 측면
