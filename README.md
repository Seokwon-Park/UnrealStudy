# 언리얼 엔진 구조 학습 노트

언리얼 엔진 구조를 공부하며 정리한 노트입니다. 노트 본문은 [`docs/`](docs/index.md)에 있습니다.

- 노트는 GitHub에서 Markdown으로 바로 읽을 수 있고,
- `main`에 푸시하면 GitHub Actions가 [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) 사이트로 빌드해 GitHub Pages에 배포합니다.

## 구조

```
docs/
  index.md              학습 지도 · 진행 상황
  template.md           새 노트 템플릿
  core/                 UObject, 리플렉션, GC
  gameframework/        Actor, Component, GameMode 등
  engine/               모듈, 빌드, 게임 루프
mkdocs.yml              사이트 설정 · 목차(nav)
.github/workflows/      자동 배포
```

## 로컬 미리보기 (선택)

```bash
pip install mkdocs-material
mkdocs serve
```
