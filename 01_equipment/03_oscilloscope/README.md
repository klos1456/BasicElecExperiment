
# Oscillosope 오실로스코프 활용

오실로스코프는 회로의 특정 지점의 전압 변화를 실시간 파형으로 측정하여 그래프로 표시해주는 계측기이다. 오실로스코프를 사용하기 위해서 실험준비실로부터 오실로스코프 프로브 케이블 2개를 가지고 오자. 고가의 장비이며 외부 전기적 영향에 민감하므로 고장 나지 않도록 주의하면서 사용한다.

--------------------
## 사용준비 

아래 그림에 오실로스코프의 전면 패널의 주요 화면을 도식화하였다. 왼쪽 하단의 전원스위치를 누르고 잠시 기다리면 부팅된 후 오실로스코프 측정 프로브에 측정되는 전압이 화면에 표시된다. 회로의 특정 노드의 전압을 측정하여 화면에서 표시하기 위해서 오실로스코프의 채널 (1번,2번)이 on이 시킨 뒤 오른쪽 상단에 Run 표시에 초록색 불이 켜져 있어야 한다. 원하는 전압이 정상적으로 측정되어 화면에 표시되지 않는다면 채널 on 및 Run버튼을 다시 한 번 확인하기 바란다.

![00_전원on](./images/00x.jpg '오실로스코프를 이용한 신호 측정 준비')

1. 왼쪽 하단의 전원 스위치를 눌러 오실로스코프전원을 켠다.
2. 오실로스코프 케이블의 단자를 오실로스코프 하단 채널 1 포트에 연결한다.
3. 1번으로 표시된 오실로스코프 입력 채널의 LED에 불이 켜져 있는지 확인한다. 꺼져 있다면 버튼을 한 번 더 누른다. 전면 LCD 화면에 표시된 각 전압파형에는 색깔로 표시되며 대응되는 채널로 현재 어느 채널 신호가 측정되고 있는지 쉽게 구분할 수 있다.
4. 기본적인 측정 방식은 Run 모드이며 이때는 측정 프로브에 관찰되는 전압의 변화를 실시간 파형으로 화면에 표시하며 순간적으로 변하는 전압 변화가 있더라도 잠시 보였다가 사라지게 된다. 버튼을 한 번 더 누르면 Stop이 되고 빨간색으로 색깔이 바뀐다. Stop되는 시점의 전압 파형을 캡처한 뒤 정지화면으로 보여준다. 



------------------
## 오실로스코프 측정 케이블

오실로스코프 장비를 이용하여 회로의 특정 노드의 전압을 측정하기 위해서는 전용 측정용 케이블을 준비해와야 한다. 케이블 단자를 본체에 연결하고 리드선 반대편 끝 측정 프로브의 클립을 측정 대상에 정확하게 결착하여야 한다. 실험 준비실로 이동하여 아래 그림과 같은 측정용 케이블 2개를 수령해오도록 한다.

![c02_오실로스코프_케이블](./images/c02.jpg '오실로스코프 케이블')

실험준비실로 이동하여 그림과 같은 오실로스코프 연결 케이블을 수령한다. 본체 연결부가 함수 발생기 케이블과 유사하므로 주의한다.

1. 오실로스코프에서 사용하고자 하는 채널을 결정하고 해당 포트를 확인한다. (채널1번, 채널 2번) 
2. 연결잭을 본체의 입력 포트에 연결한 뒤 회전하여 정확하게 결착한다. (현재 그림은 채널 1번에 연결)
3. 오실로스코프 케이블 리드선의 오른쪽 끝 Probe를 회로(브레드보드)의 측정 지점에 정확하게 연결한다. 
4. 스프링으로 조절되는 Probe 캡을 당기면 드러나는 클립을 회로의 측정 지점에 연결한다. 
5. 나머지 악어클립은 회로의 GND에 연결한다.
6. 신호 측정 배율을 선택한다. (기본은 1x, 정밀 측정시 10x로 선택, 대부분 1x모드를 사용한다.)

실험중에 간혹 Probe고장이 발생하므로 오실로스코프가 정상동작 하지 않는다고 판단된다면 먼저 케이블 불량을 의심해보는 것도 좋다. 함수발생기의 출력을 제대로 회로에 공급하지 않은 상태에서 오실로스코프 파형이 올바르게 측정되지 않은 경우도 있으므로 함수발생기의 문제도 동시에 의심해보아야 한다. 단계별로 장비의 정상 동작 여부를 순차적으로 검증하면서 실험을 진행하는 것이 좋다.



------------------
## 함수발생기 케이블

함수 발생기의 출력 전압을 회로에 공급하기 위해서는 전용 케이블을 이용하여야 한다. 실험 준비실로 이동하여 하단 그림과 같은 연결 케이블 1개를 수령한다. 본체 연결잭 모양이 오실로스코프 연결 잭과 동일할 수도 있으므로 주의한다. 

![c01_함수발생기_케이블](./images/c01.jpg '함수발생기 케이블')

1. 사용하고자 하는 함수발생기의 출력 채널을 결정한 뒤 해당 포트를 확인한다. (고정 주파수 출력 포트와 가변주파수 출력포트가 존재함) 자세한 내용은 함수발생기 섹션을 참고한다.
2. 리드선 왼쪽 끝 연결잭을 본체의 출력포트에 정확하게 삽입하고 나사를 돌려서 본체에 정확하게 결착한다.
3. 리드선 오른쪽 끝 악어 클립을 회로(브레드보드)의 특정 지점에 연결하여 회로에 교류 신호를 공급한다. 이때 신호를 공급할 회로의 특정 노드에는 빨간색 클립을 연결하고 검은색은 회로의 GND에 연결한다.

함수발생기 출력이 제대로 나오는지 항상 오실로스코프를 이용하여 출력 파형을 먼저 확인한다. (전원스위치 on상태확인, 연결잭 결착확인) 함수발생기의 출력이 올바르게 회로에 공급되지 않은 상태에서 회로의 오동작 원인을 찾는데 시간을 낭비하기 쉽다.



--------------------
## 함수발생기를 이용한 테스트 파형 준비

함수 발생기의 출력을 간단히 테스트하기 위해 TRIG OUTPUT 채널을 이용해보자. 함수발생기 하단 TRIG. OUTP.이라고 표시된 포트에 함수발생기 케이블 연결잭을 결착한다. 반대쪽 리드선 끝단의 클립을 오실로스코프와 연결하여 (빨간색은 출력전압, 검은색은 접지) 전압 파형을 측정해보면 진폭이 5V인 사각파 출력이 생성됨을 알 수 있다. 

![01_레퍼런스신호](./images/01x.jpg '함수발생기로부터 Trigger 신호 (사각파) 생성')

1. 표시된 위치의 버튼을 눌러서 함수발생기의 전원을 켠다. 
2. 함수발생기 전면 하단에 출력 포트 2개가 있으며 먼저 왼쪽 포트에 함수발생기 케이블 단자를 연결한다. (TRIG OUTP라고 표시된 포트)
3. 이 포트에는 출력 전압 5V로 진폭이 고정된 사각파만 생성된다. 즉 다른 파형의 형태 및 진폭을 조절할 수 없다.
4. 다이얼을 돌려 출력 주파수를 조절해 본다.
5. 다이얼 아래쪽에의 화살표 버튼을 이용하여 주파수 배율을 조절할 수 있다. 왼쪽 버튼을 누르면 1/10 작아지며, 오른쪽 방향 버튼을 누르면 주파수가 10x 배율로 커진다. 버튼을 누를 때마다 LCD창에 현재 선택된 주파수가 표시된다.
6. 화면에 현재 설정된 파형의 주파수를 보여준다. 숫자의 digit값과 오른쪽의 단위를 고려하여 현재 출력 주파수 가 얼마인지 적절히 판단해야 한다.
7. 함수발생기에 연결한 케이블 리드선 반대쪽 클립을 확인한다. 
8. 오실로스코프 케이블의 Probe에 그림과 같이 연결한다. (색깔에 주의하여 연결한다.)

향후 실험을 위해 함수발생기를 사용하여 가변전압, 가변주파수가 설정해야 하는데 실수로 위의 TRIG. OUTP. 포트에 출력 케이블을 연결하여 회로에 전압을 공급하는 경우가 많다. 이때 함수발생기 진폭 다이얼을 아무리 조정해도 회로에 인가되는 신호의 진폭이 가변되지 않는 현상이 발생할 경우 함수발생기의 TRIG. OUTP 채널에 연결했는지 확인하도록 하자.



--------------------
## 전면 버튼 및 다이얼 기본 사용법

함수발생기로부터 생성된 사각파를 오실로스코프로 관찰해보고, 오실로스코프 제어버튼을 이용하여 화면에 표시되는 파형의 형태를 조절해본다. 아래 그림에 오실로스코프의 전면 패널을 도식화하였다. 숫자로 표시된 것 위주로 항상 주의하면서 오실로스코프를 조심스럽게 설정해보자.

![02_스코프_기본창](./images/02x.jpg '오실로스코프 전면 다이얼 사용방법')

1. 그림과 같이 표시된 화살표 아이콘은 현재 측정 프로브의 접지 (GND, 0V) 전압 위치를 표시한다. 이 지점을 기준으로 현재 측정되는 전압의 +/- 크기를 해석할 수 있다.
2. 화면 상단에 현재 설정된 Volt/Div, 즉 수직방향으로 한칸 당 전압 크기를 표시한다. 그림에서는 한칸에 1V를 의미한다.
3. 현재 설정된 Time/Div, 즉 수평방향 한칸당 시간을 표시한다. 현재 그림에 표시된 수치는 한칸에 1ms를 의미한다.
4. 표시의 다이얼을 돌려서 현재 관찰되는 신호의 시간축 위치를 좌우로 조절할 수 있다.
5. 다이얼을 돌려서 현재 관찰되는 신호의 수직방향 위치를 위,아래로 조절할 수 있다. 1번에서 표시되는 GND위치도 같이 이동하기 때문에 화면에 표시되는 전압 파형의 위치만 바뀔 뿐이다.

--------------------
## 수직축 Volt/Div 해상도 조정

아래 그림은 측정되는 신호를 화면에 파형으로 표시할 때 수직축 해상도를 조절하기 위한 방법을 순서대로 표시한 것이다. 관찰하고자하는 전압 파형이 너무 작다면 수직축 해상도를 높여서 전압이 더 크게 보이도록 조절한다. 주의할 점은 이렇게 해상도를 높였을 때 실제로 측정된 전압이 커지는 것이 아니라 화면에 표시되는 한칸 당 전압이 작아지므로 실제로 측정되는 전압은 동일한 크기로 측정됨에 주의하자.

![03_Volt-Div변경1](./images/03x.jpg '수직축 해상도 Volt/Div 조절')

1. 다이얼을 왼쪽으로 회전 하면 Volt/Div값이 커진다. 이때 현재 입력으로 관찰되는 파형은 수직방향으로 좀 더 축소되어 표시된다. 한칸당 전압이 크므로 화면에 표시되는 파형의 크기가 작아졌지만 실제 파형의 전압이 줄어든 것이 아니므로 주의하자.
2. 다이얼을 돌리면 Volt/Div값이 실시간 업데이트 되어서 화면에 표시된다. 왼쪽으로 돌리면 Volt/Div값이 커진다. 그림에서는 2V/Div로 설정되었다. 그림의 파형을 해석해보면 수직방향으로 2.5칸을 차지하므로 2.5칸 x 2V/Div = 5V (진폭)로 해석될 수 있다. 실제로는 입력 파형의 진폭이 작아진 게 아니라 화면상에 표시된 크기만 달라졌을 뿐임에 유의하자.
3. Volt/Div을 조절하다보면 신호가 화면에 표시되는 위치가 아래나 위쪽으로 치우쳐질 수 있다. 이때 수직축 위치 조정 다이얼을 돌려서 적절한 위치로 이동시킨다. 이때 GND위치도 같이 움직이므로 신호의 진폭이 바뀐 것은 아님에 유의한다.
4. 현재 관찰되는 신호의 GND의 위치를 표시한다. 이 지점을 기준으로 Volt/Div 값을 이용하여 신호의 전압 크기를 해석할 수 있다.

3번의 수직축 GND위치 조절 버튼을 이용하여 전압의 GND 지점을 LCD 하면의 중간에 위치하도록 조절하여 전압 측정치의 마이너스 값도 올바르게 표시되도록 하자. 특히 P1, P2각각의 GND 위치가 같도록 하여 두 개의 입력 신호의 상대적인 전압차를 쉽게 비교할 수 있도록 하자.



--------------------
## 수평방향 Time/Div 해상도 조정

![04_Time-Div1](./images/04x.jpg '수평축 해상도 Time/Div 조절')

위 그림은 신호 파형의 수평축 해상도를 조절하기 위한 방법을 나타낸다. 관찰 하고자 하는 전압 파형이 시간 축으로 너무 촘촘하게 표시될 경우, 즉 관찰되는 신호의 주파수가 너무 빠를 경우 전압변화를 좀 더 세밀하게 볼 수 있도록 수평축 해상도를 높여보자. 주의할 점은 이렇게 시간 축 해상도를 높였을 때 화면에 표시되는 파형이 가로로 확대되어 표시되며 이때 관찰되는 입력 파형의 주파수가 실제로 느려지는 것이 아니라 한칸당 표시되는 시간이 작아지므로 실제로 측정되는 신호 파형의 주기는 동일하다.

1. 표시의 다이얼을 오른쪽으로 회전하면 Time/Div이 작아진다. 현재 그림은 1ms에서 500us로 작아졌다. 한 칸에 더 작은 시간 영역을 표시한다. 따라서 파형의 좁은 시간 영역을 화면에 크게 표시하므로 파형의 Zoom in 효과를 얻게 된다. 
2. LCD화면 상단에 현재 선택된 Time/Div값을 보여준다. 1번의 다이얼을 돌릴 때마다 실시간 Time/Div값이 변경되어 표시된다. 
3. 표시된 다이얼을 조절하여 파형의 수평축 위치를 적절히 이동시킬 수 있다.



-------------------------
![05_Time-Div2](./images/05x.jpg '수평축 해상도 Time/Div 조절')

1. 표시의 다이얼을 왼쪽으로 회전하면 Time/Div 값이 커진다. 현재 그림은 500us에서 1ms로 커진 상태이다. 화면의 Grid 한 칸에 더 긴 시간 영역을 표시하게 된다. 따라서 파형의 넓은 구간을 작은 영역에 표시하므로 파형의 Zoom out 효과를 얻게 된다. 
2. 현재 선택된 Time/Div값을 보여준다. 1번의 다이얼을 돌릴 때마다 현재 선택된 Time/Div값이 실시간으로 표시된다. 

수직축 해상도의 경우 P1, P2 각각 다르게 설정할 수 있는 반면 수평축 해상도는 P1, P2에 동일하게 적용되므로 시간축 scale은 항상 같이 움직인다. 반면 수직축 해상도는 P1, P2를 다르게 설정할 수 있으므로 측정하고자 하는 입력 신호의 진폭 범위를 고려하여 scale에 맞추어 전압을 해석해야 하므로 주의하도록 한다.

오실로스코프를 이용하여 전압의 시간에 따른 변화를 관찰하였다. 고가의 장비이므로 고전압/정전기 등이 장비에 인가되지 않도록 주의한다. 측정되는 예상 값을 먼저 생각해보고 원하는 값이 나오지 않을 경우 계측기가 올바르게 설정되어 있는지 먼저 확인한다. 이후에 회로의 구성이 올바르게 되어 있는지 순차적으로 분석하여 오동작 원인을 찾도록 주의하자.

원하는 전압이 나오기는 하는데 고정된 전압파형이 아니라 수평방향으로 신호가 흐르는 현상이 발생할 경우 상단 중간에 Auto Scale 버튼을 한번 눌러준 뒤 원하는 수평, 수직축 scale을 다시 설정하도록 한다. 

