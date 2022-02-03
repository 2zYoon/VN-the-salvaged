# the salvaged
Simple visual novel.

## Requirements
- `python` (3.9.10에서 테스트 됨.)
- `pygame` (2.1.0에서 테스트 됨.)

## How to Run

```bash
$ pip(3) install pygame=2.1.0

$ python(3) game.py
```

## Issues
### BGM, 효과음 재생 문제 (Windows)

레포지토리에 있는 `libmpg123-0.dll`을 `C:\Windows\System32` 및 `C:\Windows\SysWOW64`에 복사.

또는, pip 패키지가 설치된 경로에서 `pygame/libmpg123-0.dll`을 찾아, `C:\Windows\System32` 및 `C:\Windows\SysWOW64`에 복사.
