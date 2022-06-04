# OpenSource HomeWork

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

