웰컴보드 제작기 V1.2.0 · DESIGNER PRESETS

ERICA 본관 1층 16:9 디스플레이용 웰컴보드를 브라우저에서 제작하는 정적 웹 도구입니다.
설치나 서버 애플리케이션 없이 index.html과 정적 자산만으로 동작합니다.

주요 기능
- 디자이너 제공 Black·Blue·White 3종 + 기존 브라운·블랙·골드·다크 템플릿 8종
- 디자이너 시안의 예시 문구, 글자 위계, 위치, 색상, 자간·행간을 한 번에 적용하는 프리셋 버튼
- 행사명, 보조 문구, 일시, 장소 편집 및 직접 드래그 배치
- 기관 로고 최대 4개 업로드, 자동 정렬, 위치 잠금
- 4K / 6K / 8K PNG 및 PDF 출력
- 작업 JSON 저장·불러오기와 브라우저 자동 저장
- 요소 잘림, 안전 여백 이탈, 요소 간 충돌 사전 점검
- 모바일 편집/미리보기 전환과 태블릿·데스크톱 반응형 화면

사용 방법
1. index.html을 웹 서버에서 엽니다. GitHub Pages에서도 그대로 사용할 수 있습니다.
2. 디자이너 시안은 템플릿 선택 후 프리셋 버튼을 누르고, 문구와 필요한 기관 로고를 조정합니다.
3. 사전 점검에서 빨간색 차단 항목이 없는지 확인합니다.
4. 출력 화질을 고른 뒤 PNG 저장 또는 PDF 저장을 누릅니다.

저장 동작
- 입력한 설정은 브라우저에 자동 저장되고 다음 방문 때 자동 복원됩니다.
- 업로드한 로고 이미지 데이터는 개인정보·용량 문제를 줄이기 위해 브라우저 자동 저장에서 제외됩니다.
- 새 작업은 현재 자동 저장본을 지우지 않고 '직전 작업'으로 별도 보관합니다.
- 작업파일 저장은 로고를 포함한 전체 상태를 .welcome.json 파일로 내려받습니다.
- V1.0에서 사용하던 welcomeBoardMakerV10 저장 키를 유지하므로 기존 설정을 이어서 사용할 수 있습니다.

폴더 구조
welcome-board-maker/
├─ index.html
├─ README.txt
├─ logos/
│  ├─ hyu_white.png
│  ├─ hyu_erica_white.png
│  ├─ hyu_round_white.png
│  └─ hyu_lion_white.png
└─ templates/
   ├─ designer_welcome_black.png
   ├─ designer_welcome_blue.png
   ├─ designer_welcome_white.png
   ├─ thumbs/designer_welcome_black.jpg
   ├─ thumbs/designer_welcome_blue.jpg
   ├─ thumbs/designer_welcome_white.jpg
   ├─ template_13.png
   ├─ template_14.png
   ├─ welcome_template_03_classic_gold_frame.png
   ├─ welcome_template_04_gold_wave_stage.png
   ├─ welcome_template_05_modern_gold_panel.png
   ├─ welcome_template_06_brown_stage_frame.png
   ├─ welcome_template_07_black_gold_display_frame.png
   ├─ welcome_template_08_dark_gold_edge_frame.png
   └─ thumbs/ (동일 파일명의 360px JPEG 썸네일 11개)

V1.2.0 · DESIGNER PRESETS
- ZIP 제공 원본 해상도의 웰컴보드 Black·Blue·White 빈 시안 3종 추가
- 템플릿 선택은 배경만 바꾸고, 별도의 “선택 시안 프리셋 적용” 버튼으로 예시 문구와 타이포그래피를 명시적으로 적용
- 프리셋에 시안 기준 제목·보조 문구·일시·장소의 크기, 위치, 굵기, 자간·행간 저장
- Blue·White 시안의 일시·장소 라벨과 상단 ERICA 로고 배치를 함께 재현
- 기존 작업 저장 형식과 기존 템플릿 ID를 그대로 유지

V1.1.0 · FIELD STABLE
- 템플릿 경로 오류와 반복 404 제거
- 전체 원본 대신 경량 썸네일을 사용하는 템플릿 선택 UI
- 모바일 편집/미리보기 탭과 태블릿 미리보기 폭 보정
- 출력 전 경계·안전 여백·충돌 검사 및 심각한 문제의 출력 차단
- PNG/PDF 공통 출력 잠금과 진행 상태 표시
- 자동 복원 안내, 기존 저장본을 보존하는 새 작업, 중립 예시 문구
- 고급 위치·크기 설정 접기 및 키보드 포커스·44px 터치 영역 보강

출시 전 확인 기준
- Desktop 1440px / Tablet 768px / Mobile 390px
- 템플릿 11종, 프리셋 3종, 로고 0~4개, 긴 문구·충돌·화면 밖 배치
- 새 작업·자동 복원·작업파일 왕복
- 4K PNG / 8K PNG / PDF

주의
- 8K 출력은 브라우저 메모리를 많이 사용합니다. 환경에 따라 6K 또는 4K를 선택하세요.
- 로고 리사이저, PDF 벡터화 등은 이번 버전 범위에 포함하지 않습니다.
