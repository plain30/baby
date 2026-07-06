# 출산·육아용품 구매 대시보드

출산·육아용품 목록을 한눈에 관리할 수 있는 단일 HTML 대시보드입니다.

## 주요 기능

- 품목별 구매여부 체크
- 예상금액 자동 합계
- 남은 구매금액 계산
- 품목 검색
- 카테고리 / 구매상태 / 우선순위 필터
- 품목 직접 추가 및 삭제
- 브라우저 로컬 저장 기능
- CSV 내보내기
- 인쇄 및 PDF 저장

## 파일 구성

```text
baby-goods-dashboard/
├── index.html      # 메인 대시보드 파일
├── README.md       # 프로젝트 설명
└── .gitignore      # Git 제외 파일 설정
```

## GitHub 업로드 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 저장소 이름 예시: `baby-goods-dashboard`
3. 이 폴더 안의 파일을 모두 업로드합니다.
4. `Settings` → `Pages`로 이동합니다.
5. `Build and deployment`에서 다음처럼 설정합니다.
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. 저장 후 1~2분 정도 지나면 GitHub Pages 주소가 생성됩니다.

## Git 명령어로 업로드하는 방법

```bash
git init
git add .
git commit -m "Add baby goods dashboard"
git branch -M main
git remote add origin https://github.com/사용자아이디/baby-goods-dashboard.git
git push -u origin main
```

## 사용 방법

`index.html` 파일을 브라우저에서 열면 바로 사용할 수 있습니다.
GitHub Pages로 배포하면 휴대폰에서도 링크로 접속할 수 있습니다.

## 저장 방식 안내

추가한 품목, 구매 체크, 수량, 메모는 브라우저의 로컬 저장소에 저장됩니다.
다른 기기와 자동 동기화되지는 않습니다.
