- Title : A Linear Programming Approach for Synthesizing Origin-Destination(O-D) Trip Tables from Link Traffic Volumes
- Date : December 1991
- Author : R. Sivanandan
- Affiliation : Virginia Polytechnic Institute of State University


This research effort is motivated by the need to quickly obtain origin-destination (O-D) trip information for an urban area, without expending the excessive time and effort usually accompanying survey-based methods. The intent is to utilize this information to facilitate diversion of traffic in real time, in the event of congestion-causing incidents such as accidents. The O-D trip table information is a key to successful diversion planning, where user destinations are considered in developing the plans.

이 연구는 도시지역에서의 OD trip 정보를 빠르게 얻고자 하는 데서 동기부여를 받았다.
기존의 방법은 조사에 기반한(survey-based) 방법으로 시간과 노력이 많이 드는 방법이었다.
OD trip 정보를 이용하여, 교통사고와 같이 교통지체를 유발하는 사건이 발생했을 때 실시간 diversion을 만들어내는 것이 목적이다.
여기에서 diversion이란, 사고 등이 발생했을 때, 우회로를 만드는 것이다. 조금 더 정확하게는, 교통 흐름을 다른 도로나 경로로 전환시키는 것을 의미한다.
이렇게 얻는 OD trip table은 diversion planning에 있어서 핵심적인 역할을 한다.

Traffic volumes on the links of the road network contain information which can be exploited advantageously to derive the trip patterns. This approach of synthesizing a trip table from link volumes, and perhaps using a prior trip table to guide the derivation, has useful applications in the context of diversion planning. Unlike conventional O-D surveys, it has the potential of yielding results quickly, a requisite for real-time applications.

도로 네트워크에서 링크의 교통량은 trip의 패턴을 파악할 수 있는 데 사용될 수 있는 정보를 포함하고 있다.
(이 연구에서 소개하는) 링크 교통량을 가지고 trip table을 만들어내는 방법은 diversion planning에 유용하게 사용될 수 있다.
고전적인 OD survey와는 달리, 이 방법은 결과를 빠르게 낼 수 있다는 장점이 있고 따라서 실시간으로 이 정보가 사용될 수 있어서 괜찮은 잠재력을 가지고 있다.

This research work details a new methodology for synthesizing origin-destination (O-D) trip tables. The approach, which is based on a non-proportional assignment, user-equilibrium motivated, linear programming model, is the principal component of this dissertation. The model is designed to determine a traffic equilibrium network flow solution which reproduces the link volume data, if such a solution exists. If such alternate solutions exist, then it is designed to find that which most closely resembles a specified target trip table. However. it recognizes that due to incomplete information, the traffic may not conform to an equilibrium flow pattern, and moreover, there might be inconsistencies in the observed link flow data, or there might be incomplete information. Accordingly, the model permits violations in the equilibrium conditions as well as deviations from the observed link flows, but at suitable incurred penalties in the objective function. A column generation solution technique is presented to optimally solve the problem. The methodology also accommodates a specified prior target trip table, and drives the solution toward a tendency to match this table using user controlled parameters. Implementation strategies are discussed, and an illustration of the proposed method is presented using some sample test networks. The results from the model are discussed vis-a-vis other relevant, available approaches. The quality of the results and the computational effort required are used as a set of criteria in the comparisons. The comparisons of test results demonstrate the superiority of the linear programming model over the other models considered.

이 연구는 OD trip table을 만드는 새로운 방법에 대한 상세 내용을 다룬다.
이 방법은 (1) non-proportional assignment, (2) user-equilibrium (3) linear programming model에 그 기초를 두고 있으며, 이 박사논문의 핵심적인 부분이다. 이 모델은 traffic equilibrium network flow를 결정하기 위해 고안되었으며, (만약 해가 존재할 경우) 이 equilibrium은 링크의 교통량 데이터를 재생산해낸다.
만약 해가 존재할 경우 모델은 특정한 target trp table과 가장 비슷한 것을 찾는다.
하지만, 정보가 완전하지 않아서 equilibrium flow pattern이 되지 못할 수 있다.
또한, 관찰된 링크 흐름 정보가 일치하지 않거나 주어진 정보가 불완전할 수도 있다.
그러면, 이 모델은 equilibrium 조건을 조금 위반하는 것을 허용하기도 하고, 관찰된 링크 흐름 데이터와 조금 다른 것을 허용하기도 하며, 다만 목적함수에서 발생된 penalty에 의해 작동한다.
column generation solution technique은 최적으로 문제를 푸는 데 사용된다.
이 방법은 특정한 prior target trip table과 부응하며, user controlled parameters를 사용한 table과 맞도록 하는 해를 만든다.
시행의 전략에 대해 토의되고, 제안된 방법의 실례가 sample test network를 이용해 제시된다.
또한, 이 모델로부터 얻는 결과는, 그 질과 계산을 기준으로 판단하여 다른 방법과 비교된다.
그 결과, linear programming model이 여타 모델들에 비해 더 우수함을 알 수 있다.