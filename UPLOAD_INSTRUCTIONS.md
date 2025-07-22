# 📥 APK 파일 업로드 방법

APK 파일이 28.6MB로 크기 때문에 다음 방법 중 하나를 사용하여 업로드하세요:

## 방법 1: GitHub Web Interface 사용
1. https://github.com/ktgo2000/golgoru-debug 접속
2. "Add file" → "Upload files" 클릭
3. `app-debug.apk` 파일 드래그 앤 드롭
4. Commit 메시지 입력 후 업로드

## 방법 2: Git 명령어 사용
```bash
git clone https://github.com/ktgo2000/golgoru-debug.git
cd golgoru-debug
cp C:\\ktgo\\app-debug.apk .
git add app-debug.apk
git commit -m "Add app-debug.apk file"
git push origin main
```

## 방법 3: GitHub CLI 사용
```bash
gh repo clone ktgo2000/golgoru-debug
cd golgoru-debug
cp C:\\ktgo\\app-debug.apk .
gh auth login
git add app-debug.apk
git commit -m "Add app-debug.apk file"
git push
```

## 파일 정보
- **경로**: C:\\ktgo\\app-debug.apk
- **크기**: 28,555,495 bytes (28.6 MB)
- **수정일**: 2025-07-22 09:25:07

업로드 완료 후 이 파일을 삭제하고 APK 파일로 교체하세요.
