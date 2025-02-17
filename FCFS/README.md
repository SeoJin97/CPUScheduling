#FCFS Algorithm


컴퓨터 시스템의 성능향상이라는 목적을 가지며, 이 중에서 비선점방식으로 운영되는 FCFS 스케줄링이 존재한다. 
비선점이란 중간에 자리를 빼앗을 수 없다는 의미이며 다른 프로세스가 CPU를 할당받으면 그 프로세스가 작업을 종료하고 반환할 때까지 다른 프로세스가 CPU를 점유할 수 없다. 

#FCFS 스케줄링이란 
- First Come First Served 알고리즘으로, First In First Out 알고리즘이라고도 불리며 말 그대로 먼저 요청한 프로세스를 먼저 처리하는 방식이다. 
- FCFS의 장점으로는 처리 중인 프로세스에 할당된 시간을 타 프로세스가 가로채 가지 않으므로 문맥 교환이 일어나지 않아 자원의 효율성을 높인다. 
- 따라서 일괄 처리 시스템(한꺼번에 모아서 처리하는 시스템)에 적합한 스케줄링 알고리즘이다
- FCFS의 단점으로는 프로세스를 장시간 독점하는 경우 다른 프로세스들이 오래 기다려야 한다.
- 평균 응답시간이 길어질 수 있으며 우선순위가 높은 프로세스를 빨리 처리하지 못할 수도 있다. 
- 따라서 대화형 시스템(사용자와 시스템 간의 실시간 대화를 기반으로 하는 시스템)에 부적합하다.