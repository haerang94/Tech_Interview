# network

##### Transport layer
1. TCP와 UDP의 차이에 대해 설명해보세요
2. stop-and-wait 방식의 TCP 전송방식에 대해 설명해보세요
3. Pipeline 방식의 TCP 전송방식에 대해 설명해보세요
4. TCP sender가 packet loss를 감지하는 event 두 가지를 적으시오.
5. TCP에서 flow control이 필요한 이유가 무엇인가요? TCP receiver의 buffer의 역할은 무엇인가요? 
6. TCP의  connection setup 과정을 three-way handshake이라고 부르는 이유가 무엇인가요?
7. TCP의 congestion window 크기 변화 전략을 AIMD라고 한다. AIMD의 의미가 무엇인지 적으시오.  
8. TCP의 congestion control algorithm 중 slow start에서의 congestion window 크기 변경 전략을 적으시오. 
9. TCP의 congestion control algorithm은 slow start, congestion avoidance phase로 구성되는데, 이 두 phase의 congestion window 크기 조정 전략이 다른 이유가 무엇일까요? 
10. TCP가 packet loss를 three duplicate ACK으로 detect했을 때, congestion control window 크기를 변경하는 전략을 적으시오. 
11. TCP는 packet loss detection event가 무엇이냐에 따라 congestion window 크기를 줄이는 전략이 다르다. 그렇게 다른 전략을 적용하는 이유가 무엇인가?   

##### Network layer - Control plane
1. routing algorithm의 목적이 무엇인가요?
2. routing algorithm은 크게 global algorithm과 decentralized algorithm으로 나눌 수 있는데, 이 둘을 구분하는 기준은 무엇인가요?
3. link state routing algorithm의 단점으로 path oscillation가 있습니다. 이러한 현상이 일어나는 이유는 무엇인가요? 
4. distance vector routing algorithm에서 "distance vector"란 무엇을 지칭하나요? 
5. distance vector routing algorithm에서 x에서 y까지의 최소 비용 경로를 결정하는 방법을 설명하시오. 
6. 기본적인 distance vector routing algorithm에서 count-to-infinity가 발생하게 하는, 이 algorithm의 한계가 무엇인가요? 
7. Distance vector routing algorithm에서 "poisoned reverse"는 router들간의 path cost 정보 교환을 어떻게 하라고 요구하고 있나요?
