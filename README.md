# python-project-template

파이썬 기반 프로젝트의 기본 템플릿 레포입니다.

## 1. 시작하기

### 1.1. 사전 준비

#### 파이썬 버전 설치

```bash
# pyenv 설치 및 업데이트
$ brew install pyenv

# 파이썬 3.9.6 설치
$ pyenv install 3.9.6
```

#### 가상환경 및 패키지 매니저(poetry) 설치

가상환경 및 패키지 매니저로 [poetry](https://github.com/python-poetry/poetry)를 사용합니다.  
poetry는 다음처럼 설치합니다.

```bash
$ curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/install-poetry.py | python -
```

### 1.2. 프로젝트 세팅

#### 의존성 패키지 설치

```bash
$ poetry install

```

설치 후 다음처럼 가상환경에 접속합니다.

```bash
$ poetry shell
```

#### pre-commit 적용하기

```bash
$ pre-commit install
```

