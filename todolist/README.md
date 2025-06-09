# ToDo List

Python(Flask)을 이용한 간단한 ToDo List 웹 애플리케이션입니다.

## 설치

1. 가상환경 생성 및 활성화 (권장)
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows PowerShell: .\\venv\\Scripts\\Activate
   ```
2. 의존성 설치
   ```bash
   pip install -r requirements.txt
   ```

## 실행

```bash
python app.py
```

실행 후, 브라우저에서 `http://localhost:5000` 으로 접속하세요.

## 기능

- 할 일 추가
- 할 일 조회
- 할 일 완료/취소 토글
- 할 일 삭제