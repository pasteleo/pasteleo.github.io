# tech-blog — Peter의 기획 노트 (Hugo + PaperMod)

- 글은 `content/posts/`에 **blog-svc 가 승인된 초안만** 커밋한다(사람이 직접 쓰지 않는다 — 직접 쓸 일이 있으면 소재 창고 `blog-corpus` 에 넣고 큐를 통해 낸다).
- 모든 글 front matter 에 `ai_disclosure: true` → `layouts/_partials/post_meta.html` 이 고지 박스를 본문 위에 렌더한다.
- `.gitea/workflows/validate.yml`: 공개안전 검사 통과 시에만 GitHub `pasteleo/pasteleo.github.io` 로 미러 → `.github/workflows/hugo.yml` 이 Pages 빌드.
- 설계: ai-native-homelab `docs/design/2026-09-25-tech-blog.md`.
