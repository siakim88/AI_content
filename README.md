# 자막 기반 AI 교육 자동화 메뉴얼

이 저장소는 Make.com / n8n을 활용해 중국어 교육 콘텐츠를 자동 생성·배포하는 전체 워크플로우를 정리합니다.

## 구성
- `workflows/` : Make, n8n 블루프린트(JSON, .blueprint.json)
- `prompts/`   : OpenAI/Claude 프롬프트
- `docs/`      : 자세한 사용 가이드(이미지, 단계별 튜토리얼)
- `html-templates/` : HTML 템플릿, CSS/JS
- `samples/`   : 예시 출력(HTML/PDF/이미지)

## 빠른 시작
1. `docs/quickstart.md`를 먼저 읽으세요.
2. `workflows/`의 블루프린트를 가져와 Make/n8n에 임포트합니다.
3. `prompts/` 폴더의 프롬프트를 붙여넣고 변수만 교체합니다.

## 라이선스 / 문의
- 저작권: © 2025 SIA KIM
- 문의: 이슈 탭에 등록해주세요.
