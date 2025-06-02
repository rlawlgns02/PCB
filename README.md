# PCB제작하기<br>

## PCB제작 과정 <br>
## 1. PCB 만드는 프로그램 다운로드
- `https://www.kicad.org/` 이곳에서 다운로드 가능
- 자신의 운영체제에 맞는 버전 설치
<br>
## 2. 파일 - 새 프로젝트 생성
- 프로젝트를 만들고 `본인 프로젝트 이름.kicad_sch` 클릭
- **기본 전역 심볼 라이브러리 테이블 복사** 선택후 확인 클릭<br>
![Image](https://github.com/user-attachments/assets/1a6c81e8-8666-4630-913a-2761a30b083a)


### 기본 조작법
- 휠을 통해서 확대 - 축소
- 화면이 너무 커지거나 작아질 경우 키보드 Home 버튼을 통해서 딱 맞게 설정
- 휠클릭을 통해서 화면 이동
- alt + 휠 = 위아래 스크롤
- ctrl + 휠 = 좌우 스크롤
- R = 90도 회전
- A = 심볼 배치
- P = 전원 심볼 배치
- W = 전선 그리기<br>
## 3. 회로도 그리기
**심볼 배치 (A)**
- 원하는 심볼 배치를 통해서 원하는 심볼을 배치 한다<br>
**전원 심볼 배치 (P)**
- 원하는 전원 심볼을 찾아서 배치 한다.<br>
**선 그리기 (W)**
- 전선을 올바르게 연결 한다 <br>
**풋프린트**
- 각 알맞는 Footprint를 설정한다 <br>
**회로도 예시 사진**
![Image](https://github.com/user-attachments/assets/9a98c5c5-fd8e-4320-82ab-d9c994d64acb)

## 4. PCB 그리기
- `본인프로젝트.kicad_pcb`를 클릭
- 회로도에서 PCB 업데이트 (F8)
- 대략적으로 위치를 원하는대로 수정한 후 사각형 그리기를 통해 크기 설정
- 단선 배치(X)를 통해서 전선 배치
![Image](https://github.com/user-attachments/assets/5899eb8b-bfed-459b-9aeb-95353b3ee21e)
- 3D뷰어를 이용해서 예상 모습을 볼 수 있다
![Image](https://github.com/user-attachments/assets/18c889ff-a8cb-48ac-be46-cec75d2798f8)
## 5. 기판 제조 출력 
- 파일 - 기판 제조 출력 - 거버 파일(.grb)
- 출력 디렉토리를 본인의 프로젝트 디렉토리 하위 디렉토리에 `gerber`를 생성후 플롯 버튼 클릭
- 플롯을 클릭 한 후에 드릴 파일 생성 클릭후 생성 클릭
- 거버 파일을 열어서 제대로 만들어 졌는지 확인<br>
![Image](https://github.com/user-attachments/assets/69c56070-c518-442c-a204-a305aee185d9)
