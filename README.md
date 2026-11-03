# IMAGE LAB — AI 이미지 분류 사이트

Teachable Machine 이미지 분류 모델을 이용해 사진을 **강아지 / 고영희 / 뱀**으로 분류하는 웹사이트입니다.

## 실행
- `index.html`을 VS Code Live Server로 실행하거나 GitHub Pages로 배포하세요.
- `model/` 폴더에 `model.json`, `metadata.json`, `weights.bin`이 모두 있어야 합니다.
- **중요:** `model/model.json`은 현재 패키지에서 원본을 자동으로 포함하지 못해 안내용 임시 파일입니다. 업로드한 원본 `model.json`으로 반드시 교체해야 모델이 작동합니다.

## GitHub 업로드 및 Pages 배포
1. GitHub에서 `New repository`를 눌러 Public 저장소를 만듭니다.
2. 이 폴더 안의 `index.html`, `README.md`, `model` 폴더를 저장소 루트에 업로드합니다.
3. `model` 폴더 안에 세 모델 파일이 있는지 확인합니다.
4. `Settings` → `Pages` → `Deploy from a branch`를 선택합니다.
5. Branch `main`, Folder `/(root)`를 선택하고 `Save`를 누릅니다.
6. 몇 분 뒤 Pages 화면에 표시되는 주소로 접속합니다.

## 폴더 구조
```text
image-classifier/
├── index.html
├── README.md
└── model/
    ├── model.json
    ├── metadata.json
    └── weights.bin
```

## 사용 기술
HTML, CSS, JavaScript, TensorFlow.js, Teachable Machine Image
