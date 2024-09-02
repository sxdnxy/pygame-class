# pygame-class


## 셋팅

- Terminal -> New Terminal
- Command Prompt 열기 (+버튼 옆에)
- `python -m venv .venv` (생략)
- `.\.venv\Scripts\activate.bat`
- ---> (.venv) 가 보여야 함.

- 처음 패키지 설치
```shell
pip install pygame-ce
pip install black isort
pip freeze > requirements.txt
```

- 패키지 재설치 (requirements.txt가 있을 경우)
```shell
pip install -r requirements.txt
```
pip uninstall pygame-ce
pip install pygame
pip freeze > requirements.txt
