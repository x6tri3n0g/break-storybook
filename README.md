# Storybook 부시기

> [React Storybook](https://storybook.js.org/tutorials/intro-to-storybook/react/ko/get-started/) 참고

## Setting React Storybook

리액트 스토리북을 설정하기 위해서는 `degit`을 사용하여 빌드 시스템을 설정합니다.
이 패키지를 사용해 템플릿(일부 기본 구성으로 부분적 구축된 애플리케이션)을 다운로드해 개발 작업 흐름(workflow)을 빠르게 파악할 수 있습니다.

```
# Clone the template
npx degit chromaui/intro-storybook-react-template taskbox

cd taskbox

# Install dependencies
yarn
```

> 템플릿에는 튜토리얼 버전에 필요한 스타일, assets 및 기본 구성이 포함되어 있습니다.

다양한 환경에서 애플리케이션이 올바르게 동작하는지 아래 명령어를 통해 확인합니다.

```
# Run the test runner (Jest) in a terminal:
yarn test --watchAll

# Start the component explorer on port 6006:
yarn storybook

# Run the frontend app proper on port 3000:
yarn start
```
