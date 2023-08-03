
![header](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=300&section=header&fontSize=35&text=State%20Management&animation=fadeIn&fontAlignY=42&fontAlign=20)

### Contetents

<br/>

#

### Stage management

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://docs.flutter.dev/assets/images/docs/development/data-and-backend/state-mgmt/state-management-explainer.gif" width="400" height="200"><br/>

<br>

##### Thinking declaratively

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://docs.flutter.dev/assets/images/docs/development/data-and-backend/state-mgmt/ui-equals-function-of-state.png" width="400" height="200"><br/>

- Flutter는 UI를 일부분 수정하기보다 모든 프레임을 처음부터 다시그려도 괜찮다. 그만큼 빠르기 때문이다
- 이러한 속도로 flutter는 선언형이 가능해진다. 함수를 재선언해서 ui를 다시그려도 될만큼 빠르다는 것이다
- 만약 앱에 어떠한 변화가 생기면 (터치하든가 등등) **state**를 바꾸게 된다. 그리고 이러한  **state**변화는 UI를 첨부터 다시 그리게 된다
- 이러한 선언형 방식의 UI그리기 방법은 특정 ui그리기 방식을 한가지로 제한함으로서 어떤 상태에서도 이걸 그대로 대입만 하면 똑같이 보이게 한다
- 

<br/>

#

### Ephemeral state




