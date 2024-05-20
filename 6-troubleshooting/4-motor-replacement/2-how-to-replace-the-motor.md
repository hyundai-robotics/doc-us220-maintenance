﻿# 6.4.2. 모터 교환 방법

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-b001{background-color:#f8ff00;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-b001"><img src="../../_assets/작은주의표시.png"> 주의</td>
    <td class="tg-cly1">본 로봇은 암의 자세 유지용 브레이크가 모터에 내장되어 있으므로 모터를 분리하면 암이 낙하합니다. 따라서 낙하를 방지하기 위해 크레인 등으로 암을 매달고, 고정용 볼트를 삽입하여 암을 고정시키는 안전대책을 반드시 행해야 합니다.</td>
  </tr>
</thead>
</table>


(1)	제어기를 티칭 모드로 하고, 운전준비 [ON] 상태로 합니다. 

(2)	모터를 교환하는 축의 기본자세를 취합니다. 모터의 운전준비 [ON]이 안되거나, 모터의 축을 움직일 수 없는 경우, (3)부터 작업합니다.

(3)	2, 3축의 모터를 교환 할 시, 그림 6.1 ~ 그림 6.2을 참고하여 암 낙하방지 고정 볼트를 삽입합니다. 고정볼트를 삽입 할 수 없는 경우 크레인 등을 이용하여 낙하방지조치를 취하십시오.

(4)	제어기 전원을 [OFF] 상태로 하고 1차 전원을 [OFF] 합니다.

(5)	모터 배선을 분리해 주십시오.

(6)	모터 취부 볼트를 제거하여 로봇 본체에서 모터를 분리합니다.
2(H), 3(V)축 모터를 분해할 때, 모터 축에 취부된 기어에 인해, 오일씰의 립이 손상되지 않도록 주의하여 주십시오.

(7)	모터 축에 취부되어 있는 기어를 분리 하십시오. 
이때, 모터 축에 강한 충격이 가해지지 않도록 주의하십시오.

(8)	신규 모터의 축에 그리스를 얇게 도포하고, 기어를 조립합니다.
이때, 모터 축에 기어를 체결하는 볼트는 세척, 탈지 후 나사부에 풀림 방지용 본드 (Loctite 243)를 나사 체결면 전체에 도포하십시오. 토크 렌치를 사용하여 규정된 토크로 체결하십시오. 또한, 모터를 로봇 본체에 체결할 때, 볼트체결 순번을 대칭방향으로 체결하십시오.

(9)	오일씰의 립 부위에 그리스를 소량 도포하고, 모터를 로봇 본체에 조립 하십시오. 주축 모터를 취부할 때는 기어 치면에 의해 오일씰의 립이 손상되지 않도록 주의해 주십시오.

(10) 모터 배선을 연결하십시오.

(11) 2(H), 3(V)축 모터를 교환한 경우, 유출된 그리스만큼 새 그리스를 주입해 주십시오.

(12) 모터 교환한 축의 엔코더를 리셋합니다.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-b001{background-color:#f8ff00;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-b001"><img src="../../_assets/작은주의표시.png"> 주의</td>
    <td class="tg-cly1">엔코더 보정을 하기 전에, 일단 운전준비 [ON]으로 해서, 티치펜던트의 Enable 스위치를 2∼3초간 누르면서 전원이 들어가는지 확인합니다.</td>
  </tr>
</thead>
</table>

(13) 모터 교환한 축의 엔코더는 “Hi6 제어기 조작설명서 7.4.4엔코더 옵셋”을 참조해서 보정하십시오.

(14) 2(H), 3(V)축 ARM 낙하 방지용 M20 볼트를 분해 합니다. 또는, 이외의 낙하방지조치를 해제하십시오.

(15) 로봇 동작에 문제가 없는지 확인 합니다.



![](../../_assets/그림_6.1_arm축_고정용_볼트_삽입_위치.png)

그림 6.1 Arm(2(H)축) 고정용 볼트 삽입 위치


![](../../_assets/그림_6.2_arm축_고정용_볼트_삽입_위치.png)

그림 6.2 Arm(3(V)축) 고정용 볼트 삽입 위치
