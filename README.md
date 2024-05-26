# VSCODE 활용 단축키

### 주석 (comment)
* <span style="color.red">#</span> : 한줄(Line) 주석 토글 
* <span style="color.red">Ctrl + l</span> : 여러줄을 #로 주석처리  
* <span style="color.red">''' '''</span> : 여러줄을 문자열화 시키기. --> 코드나 함수 등 무언가를 설명해야하는 부분에 주로 사용  
* <span style="color.red">""" """</span> : 동일하게 여러줄을 문자열화 시킵니다.

### 들여/내어쓰기
* <span style="color.red">tab</span> : tab 간격만큼 코드를 안쪽으로 들입니다. (여러줄 드래그 후 tab은 여러줄 들이기)
* <span style="color.red">shift + tab</span> : tab 간격만큼 들여쓰기 된 코드를 다시 뺌
    * (shift + tab 같은 경우에는 반복문을 쓰다가 해당 반복문을 삭제하고 내부 코드 전체를 한꺼번에 밖으로 빼고 싶을 때 사용가능)

### 들여쓰기(탭) 간격 설정
* ctrl + shift + p 누르고 Indent Using Spaces 또는 Indent Using Tabs 검색.
* 그리고 들여쓰기 간격 숫자 조정

### 여러줄을 한 줄로 / 한 줄을 여러줄로 
* ; : 세미콜론은 한 줄에서 여러개의 명령어를 사용하려 할 때 사용합니다. 보통 초기에 변수를 지정할 때 사용합니다.
* \ : 코드가 길어져서 화면 밖으로 나갈 정도로 길어진다면, 해당 코드를 두 줄에 걸쳐서 작성하는 것이 더 보기 좋을 것입니다. 코드를 작성하다 \를 넣으면, 아랫줄로 한 칸 내려와서 그 뒷부분의 코드를 작성할 수 있습니다.


### 강제종료
* ctrl + c : 강제종료 (무한루프에 빠졌을 때 종료 가능)
  
### HTML 초기태그
* ! + Tab

### 에디터 기본 단축 기능
* Ctrl + F : 일치하는 텍스트 찾기
* Ctrl + H : 일치하는 텍스트 바꾸기
  * 대문자 구별
  * 단어완전일치
  * 정규식
  * 하나씩 바꾸기
  * 모두 바꾸기
 
* Ctrl + , (콤마) : 설정창 열기
* Ctrl + ` (백틱) : 터미널 열기/닫기
* Ctrl + B : 왼쪽 탐색기 창 끄기/켜기
* Ctrl + '+' : 폰트 키우기
* Ctrl + '-' : 폰트 줄이기
* Ctrl + 1 or 2 : 좌측 또는 우측 화면으로 포커스 하기
* Ctrl + Pageup / Pagedown : 열어놓은 탭 왔다갔다 하기
* Ctrl + p : 메뉴에서 찾지말고, 파일 검색해서 빠르게 파일 열기

## 코딩하는데 편한 단축키
Shift + Alt + F / 전체 선택후 Ctrl + K + F: 자동정렬
* 단축키를 누르면 자동 들여쓰기 및 스타일 포맷을 한 번에 맞출 수 있음
* 매우 많이 사용되는 플러그인(plug-in)
  
<br/>
Ctrl + G : 해당 라인으로 이동  
* 100번째 줄로 이동할 경우 100을 입력
<br/><br/>
F12 / Ctrl + 클릭 : 해당 함수 정의문으로 바로 이동
<br/><br/>
Alt + F12 : 해당 함수 정의문 엿보기
  * 바로 이동하지않고 미리보기 툴바를 띄움
<br/><br/>
Shift + Alt + (↑, ↓) : 한줄 복사
<br/><br/>
Alt + (↑, ↓) : 한줄 이동
<br/><br/>
Ctrl + Shift + k / Ctrl + x : 한줄 삭제
<br/><br/>
Ctrl + L : 코드 한 라인 블록으로 묶기
* 연속으로 하면 쭉 내려가며 묶어진다.
<br/><br/>
Ctrl + D : 같은 단어 하나씩 선택 (밑으로 하나씩 선택됨) 
<br/><br/>
Ctrl + Shift + L : 같은단어 전체 선택
<br/><br/>
Alt + Click : 멀티 커서
* 여러군데 눌러서 한번에 수정가능
<br/><br/>
Ctrl + Alt + (↑, ↓) : 길다란 커서
<br/><br/>
Shift + Alt + 마우스 드래그 : 자유 영역 지정
<br/><br/>
Alt + Shift + I : 드래그된 모든 줄의 끝에 커서를 모두 생성
<br/><br/>
드래그 + ( : 문자를 자동으로 괄호로 묶어준다.
<br/><br/>
Alt + Shift + a : 블록 주석 묶기
* 주석으로 묶을 코드 부분을 드래그하고 단축키를 누르면 주석 처리 된다.

# ANACONDA (가상환경) 사용법
1. 가상환경 생성, 활성화, 비활성화, 삭제.
2. 패키지 설치, 업데이트, 삭제.
3. Jupyter Notebook 실행.
4. 문제 해결 및 환경 설정.


### 1. 가상환경 관리
#### (가상환경 생성)
`conda create --name <env_name> python=3.9.13` 생성 후 python 설치까지  
  
`conda create --name <env_name>`  가상환경 생생 이후 따로 python 설치  
`conda install python=<version>`  

#### (가상환경 활성화 / 비활성화)
`conda activate <env_name>`  
`conda deactivate`  
#### (가상환경 삭제)
`conda remove --name <env_name> --all`  

### 2. Anaconda 패키지 관리
`conda` 명령어를 사용하여 패키지를 설치, 업데이트 및 삭제할 수 있다.  

#### (패키지 설치)
`conda install <package_name>`  
ex) conda install pandas numpy  
#### (패키지 업데이트)
`conda update <package_name>`  
#### (패키지 삭제)
`conda remove <package_name>`  
#### (설치된 패키지 목록 확인)
`conda list`  
#### (특정 환경의 패키지 목록 확인)
`conda list --name <env_name>`  

### 3. Jupyter Notebook 실행
Anaconda에는 Jupyter Notebook이 포함되어 있어, 가상환경에서 jupyter Notebook을 실행할 수 있습니다.  
#### (Jupyter Notebook 설치)
`conda install jupyter`  
#### (Jupyter Notebook 실행)
`jupyter notebook`

### 4. 문제 해결
#### (가상환경에 필요한 패키지 설치)
필요한 패키지를 가상환경에 설치하려면, 먼저 가상환경을 활성화한 후 패키지를 설치합니다.  
`conda activate myenv`  
`conda install <package_name>`  

#### 설정 파일을 통해 환경 설정  
사용자 정의 설정을 추가하기 위해 설정 파일을 편집할 수 있습니다.  
예: Jupyter 설정 파일 생성  
`jupyter notebook --generate-config`  
생성된 설정 파일 (~/.jupyter/jupyter_notebook_config.py)을 편집하여 원하는 설정을 추가합니다.

### 6. 환경 정보 확인
#### (가상환경 목록 보기)  
`conda info --envs`  
이 명령어를 사용하면 설치된 모든 가상환경의 목록을 볼 수 있습니다.

#### (가상환경 정보 확인)  
`conda list --name <env_name>`


















