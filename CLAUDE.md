# CLAUDE.md

이 파일은 저장소에서 작업할 때 Claude Code(claude.ai/code)에게 제공되는 안내 문서입니다.

## 프로젝트 개요

단순 정적 웹 프로젝트입니다. 빌드 도구, 패키지 매니저, 서버가 없으며 브라우저에서 직접 실행됩니다.

## 실행 방법

```bash
open index.html
```

또는 브라우저에서 파일을 직접 열면 됩니다.

## 구조

현재 단일 파일(`index.html`) 안에 HTML, CSS, JavaScript가 모두 포함되어 있습니다.

- **HTML**: 페이지 레이아웃 및 요소
- **CSS**: `<style>` 태그 내 인라인 스타일 (다크 테마, 반응형)
- **JS**: `<script>` 태그 내 인라인 스크립트 — `quotes` 배열, `updateQuote()`, `nextQuote()`, `randomQuote()` 함수
