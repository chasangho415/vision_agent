# panorama.py
## 사진 봉합
영상을 조금씩 돌려 여러장을 찍어 봉합하여 파노라마를 만든다.

### 주요 기능
- [스크립트가 제공하는 기능 목록]
  - 영상 수집
  - 찍은 영상 보기
  - 봉합
  - 저장
  - 나가기

# 요구 사항

스크립트를 실행하기 전에 다음과 같은 의존성 라이브러리를 설치해야 합니다:

```bash

pip install opencv-python opencv-contrib-python
pip install numpy
pip install PyQt6
pip install pyinstaller
pyinstaller --onefile --noconsole .py위치
