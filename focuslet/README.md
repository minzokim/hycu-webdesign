# Focuslet Download Page

Focuslet 뽀모도로 타이머 앱 다운로드 페이지입니다.

## 파일 구성

```text
focuslet-site/
├─ index.html
├─ app_icon.png
├─ screen.jpg
├─ README.md
└─ .gitignore
```

## 업로드 방법

1. GitHub에서 새 Repository를 만듭니다.
2. 위 파일들을 Repository의 최상단/root 위치에 업로드합니다.
3. `index.html`, `app_icon.png`, `screen.jpg` 세 파일이 같은 위치에 있어야 합니다.
4. Repository의 `Settings` → `Pages`로 이동합니다.
5. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
6. Branch는 `main`, 폴더는 `/root`로 설정합니다.
7. 저장 후 잠시 기다리면 GitHub Pages 주소가 생성됩니다.

## 주의

- 이미지 파일명을 바꾸면 HTML에서 이미지가 보이지 않습니다.
- APK 파일은 Google Drive 링크로 연결되어 있습니다.
- 앱 소개 페이지는 정적 HTML이라 별도 서버가 필요 없습니다.
