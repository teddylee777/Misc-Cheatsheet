# TIL in LAB 

연구실 생활을 하다보면 나만 모르고 있는 것 같은 컴퓨터 코드를 모아두는 작고 소중한 저장소입니다.

## Linux 

### [Server](linux/server.md)

- 서버 간 파일 전송하기 (`scp`)
- 외부 localhost 접속하기 (`ngrok`)
- 서버 password 변경하기 (`passwd`)

### [GPU](linux/gpu.md)

- 사용 GPU 지정 Python (`CUDA_VISIBLE_DEVICES`)
- CUDA 버전 확인하기 (`nvcc`)
- GPU 사용량 확인하기 (`nvidia-smi`)
- GPU 사용량 확인하기 2 (`nvtop`)

### [Util](linux/util.md)

- 노트북을 덮거나 시간이 지나도 꺼지지 않게 (`caffeinate`)
- 파일 개수를 알고 싶다면? (`ls -l | grep ^- | wc -l`)
- 디스크의 남은 용량을 알고 싶다면 (`df -h`)
- Syntax Highlight와 함께 cat을 쓰고 싶다면 (`bat`)

## Web Programming

### [Flask](web_programming/flask.md)

- Flask에 캐시가 쌓여 새로고침이 안된다면?

---

## Reference

- [Modern Unix](https://github.com/ibraheemdev/modern-unix)
  - 짱짱 멋진 command 명령어 모음