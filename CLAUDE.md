# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 언어 및 커뮤니케이션 규칙

- **기본 응답 언어**: 한국어
- **코드 주석**: 한국어로 작성
- **커밋 메시지**: 한국어로 작성
- **문서화**: 한국어로 작성
- **변수명/함수명**: 영어 (코드 표준 준수)

## 프로젝트 개요

초기 단계의 HTML 프로젝트로 현재 `index.html` 파일만 포함되어 있습니다.

## 프로젝트 구조

- `index.html` - 진입점 템플릿 (현재 빈 body)

## 개발 환경

### 시작하기

현재 프로젝트는 빌드 프로세스나 의존성이 필요하지 않습니다. 로컬에서 사이트를 보려면:

```bash
# Python 3 사용
python -m http.server 8000

# 또는 Node.js의 http-server 사용
npx http-server
```

### 기능 추가 시 고려사항

프로젝트가 성장함에 따라 다음을 추가할 수 있습니다:

1. **빌드 도구** - CSS/JS 자산 처리 필요 시 빌드 명령어 문서화
2. **패키지 관리** - Node.js 의존성 추가 시 `npm install` 지침 포함
3. **테스트** - 테스트 추가 시 실행 방법 문서화
4. **코드 검사** - 코드 품질 도구 도입 시 lint 명령어 문서화

## 향후 개발 지침

프로젝트 발전에 따라 이 파일을 다음 항목으로 업데이트하세요:
- 새로운 명령어 (build, test, lint, dev server)
- 아키텍처 결정 사항
- 의존성 정보
- 주요 파일 위치 및 목적
