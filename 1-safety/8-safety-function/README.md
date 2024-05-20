# 1.8 안전기능

로봇의 안전 시스템은 [ISO13849-1:2015]의 안전성능(PL)=d Cat3와 [IEC62061:2005]의 안전무결성수준(SIL) 레벨2을 만족시키기 위해 이중화(HFT=1) 설계되었으며, 안전 관련 디바이스의 상태를 지속적으로 모니터링합니다. 자가진단에 의한 에러 검출 또는 안전 관련 신호가 입력되면 위험성평가에 의해 결정된 정지 분류에 따라 로봇을 정지시킵니다. 또한, 안전회로의 이중화 스위치 중 어느 하나라도 활성화되었을 경우 모터 구동 전원과 브레이크 구동 전원을 차단하여 안전한 상태가 되도록 합니다. 해당 상태에 대한 정보는 티치펜던트를 통해 확인 가능합니다.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cgy6{background-color:#fe0000;color:#ffffff;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-cgy6"><img src="../../_assets/작은주의표시.png"> 위험</td>
    <td class="tg-0lax">안전 회로는 어떠한 방법으로든 결코 무시하거나, 수정, 변경되지 않도록 하십시오.</td>
  </tr>
</thead>
</table>

<br>
로봇의 안전 관련 주요한 기능은 아래와 같습니다.
