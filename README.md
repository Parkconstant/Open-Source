# OpenSource HomeWork
---
|Linux 명령어|설 명|
|:---:|:---:|
|top|시스템의 상태를 전반적으로 가장 빠르게 파악 가능(CPU, Memory, Process)하다.|

|top 실행 후 명령어|설 명|
|:---:|:---|
|shift + p|CPU 사용률이 높은 프로세스 순서대로 표시|
|shift + m|메모리 사용률이 높은 프로세스 순서대로 표시|
|shift + t|프로세스가 돌아가고 있는 시간 순서대로 표시|
|- k|프로세스  kill  - k 입력 후 종료할 PID 입력 signal을 입력하라고 하면 kill signal인 9를 입력|
|- a|메모리 사용량에 따라 정렬|
|- b|Batch 모드 작동|
|- c|명령행/프로그램 이름 토글|
|- d|지연 시간 간격은 다음과 같다. -d ss. tt (seconds.tenths)|
|- h|도움말|
|- H|스레드 토글|
|- i|유휴 프로세스 토글|
|- m|VIRT/USED 토글|
|- M|메모리 유닛 탐지|
|- n|반복 횟수 제한 : -n number|
|- p|PID를 다음과 같이 모니터 : -pN1 -pN2 ... or -pN1, N2 [, ...] |
|- s|보안 모드 작동|
|- S|누적 시간 모드 토글|
|- u|사용자별 모니터링 : -u somebody|
|- U|사용자별 모니터링 : -U somebody|
|- v|version|
|space bar| refresh|
|- u|입력한 유저의 프로세스만 표시 - which u|

![top사진](https://user-images.githubusercontent.com/101575152/172018432-4df1b663-622a-422a-8407-0d67b2d1d6c1.PNG)
**설명**  
02:23:26 현재 서버의 시간  
0user : 0명의 사용자가 접속  
load average : 부하율  
tasks 에서 4 total은 3개의 프로세스가 가동중  
1 running : 1개의 프로세스가 실행중  
3 sleeping : 3개의 프로세스가 대기중  
0 stopped : 0개의 프로세스가 멈춤  
0 zombie : 0개의 프로세스가 좀비상태  

**-- 프로세스 상태 --**  
PID : 프로세스 ID (PID)  
USER : 프로세스를 실행시킨 사용자 ID  
PRI : 프로세스의 우선순위 (priority)  
NI : NICE 값. 일의 nice value값이다. 마이너스를 가지는 nice value는 우선순위가 높음.  
VIRT : 가상 메모리의 사용량(SWAP+RES)  
RES : 현재 페이지가 상주하고 있는 크기(Resident Size)  
SHR : 분할된 페이지, 프로세스에 의해 사용된 메모리를 나눈 메모리의 총합.  
S : 프로세스의 상태 [ S(sleeping), R(running), W(swapped out process), Z(zombies) ]  
%CPU : 프로세스가 사용하는 CPU의 사용율  
%MEM : 프로세스가 사용하는 메모리의 사용율  
COMMAND : 실행된 명령어  

---
|Linux 명령어|설 명|
|:---:|:---:|
|ps [옵션]|ps명령어는 현재 실행중인 프로세스 목록을 보여준다.|
|-e|모든 프로세스를 출력해 준다.|
|-f|풀 포맷으로 보여준다.(UID, PID 등)|
|-l|긴 포맷으로 보여준다.|
|p, -p|특정 PID의 프로세스를 보여준다.|
|-u|특정 사용자의 프로세스를 보여준다.|

![ps이미지](https://user-images.githubusercontent.com/101575152/172019524-49d2d722-cc2c-47f3-9a28-39ef4750ea05.PNG)  
ps : pid, cmd 등 기본적인 내용만 출력된다. 옵션 없이는 잘 사용하지 않는다.  

![ps -ef](https://user-images.githubusercontent.com/101575152/172019573-833c4640-24cd-45af-8bbc-660c4fdc26e9.PNG)  
ps -ef : 모든 프로세스를 풀 포맷으로 보여준다.  

---

