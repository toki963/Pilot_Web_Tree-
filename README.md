# Branch — 대화형 트리 편집기

React + TypeScript + Vite 기반의 브라우저 트리 편집기입니다.

## 실행
Node.js 20 이상 권장

```bash
npm install
npm run dev
```

터미널에 표시된 주소(보통 http://localhost:5173)를 여세요.

프로덕션 빌드: `npm run build`

## 주요 기능
- 노드 추가, 드래그 이동, 더블클릭 이름 변경
- 자식 추가, 노드 선택, 삭제
- 연결 핸들로 부모 관계 편집 및 순환 관계 방지
- 가지 접기/펼치기
- 확대/축소, 캔버스 이동, 미니맵, 전체 화면 맞춤
- 이름·설명·색상 편집
- LocalStorage 자동 저장
- JSON 가져오기/내보내기
- PNG/SVG 내보내기
- Undo/Redo 단축키
- 반응형 편집 패널

데이터는 브라우저에 저장되며 서버 동기화는 포함하지 않습니다.