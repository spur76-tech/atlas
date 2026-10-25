# 아틀라스 (인체 아틀라스 3D)

- 정적 사이트, GitHub Pages: https://spur76-tech.github.io/atlas/
- 코드는 index.html 한 파일, 3D 모델은 models/*.glb, Three.js r128
- 모든 답변과 보고는 한국어로

## 작업 순서
1. 새 기능 → architect 가 설계와 분배
2. 3D 코드 → threejs-developer / 화면 → ui-developer / 해부학 내용 → anatomy-content
   근육 이름을 넣거나 고쳤으면 → muscle-name-checker 로 한글 명칭 확인
   운동 동작·시뮬레이터를 넣거나 고쳤으면 → movement-checker 로 근육 역할·관절 움직임·각도 확인
3. 구현 후 → security 점검 → test 실행 → code-reviewer 최종 검토
4. 커밋은 code-reviewer 가 "커밋 가능"이라고 한 뒤에만
