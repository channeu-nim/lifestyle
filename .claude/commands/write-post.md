---
description: 작가·편집자·독자 에이전트가 토론하며 글 한 편을 완성한다
argument-hint: <주제> [| 독자 페르소나]
---
주제: $ARGUMENTS

아래 순서로 진행해라. 파일은 `content/<슬러그>/` 아래에 저장한다.

1. **초안**: writer 에이전트에게 초안을 쓰게 한다 → `draft-v1.md`
2. **피드백 (병렬)**: editor와 reader 에이전트를 동시에 호출해 v1을 검토시킨다 → `feedback-editor.md`, `feedback-reader.md`
3. **수정**: 두 피드백을 writer에게 넘겨 고쳐 쓰게 한다. 받아들인/거절한 피드백 목록을 함께 남긴다 → `draft-v2.md`, `revision-notes.md`
4. **최종 검토**: editor가 v2에 점수를 매긴다. 8점 미만이면 3~4단계를 한 번 더 반복한다.
5. 최종본을 `final.md`로 저장하고, v1→최종본에서 무엇이 바뀌었는지 사용자에게 5줄 이내로 보고한다.
