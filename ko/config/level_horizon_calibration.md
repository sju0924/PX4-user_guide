# 수평 보정

*수평 보정* 작업은 장치들의 미세한 방향 오차를 보정하고, *QGroundControl* 비행 시야의 수평(파란색이 위로, 녹색이 아래로 가게)을 보정합니다.

:::tip
수평 보정을 강력히 권고합니다. 최고의 비행 성능을 나타낼 수 있습니다. 비행중에 일정한 표류현상이 나타나는 경우에도 이 과정을 반복 할 수 있습니다.
:::

## 보정 작업

-- 수평 보정

1. *QGroundControl*을 시작하고 기체를 연결합니다.
2. 상단 도구 모음에서 **톱니바퀴** 아이콘(기체 설정)을 선택한 다음 가장자리 표시줄에서 **센서**를 선택하십시오.
3. **수평 조정** 단추를 누르십시오. :::note 이미 비행 방향 설정</ 1>이 설정되어 있어야합니다. 미리 설정하지 않았다면, 여기에서 설정할 수 있습니다. :::</li> 
    
    * 기체를 방향을 유지한 채로 평평한 바닥에 두십시오: 
        * 비행기의 경우 이 자세가 수평 비행 자세입니다 (비행기는 날개가 약간 올라가는 경향이 있습니다!).
        * 헬리콥터의 경우 이 자세가 부양 자세입니다.
    * 보정 작업을 시작하려면 **확인**을 누르십시오.
    * 보정 작업이 끝날 때까지 기다리십시오.</ol> 
    
    ## 검증
    
    방향이 설정되고 수평 수평 보정이 완료되면 비행 뷰에서 차량을 북쪽으로 향할 때 나침반의 방향이 0 부근의 값을 표시하고 수평이 수평인지 확인합니다 (상단은 파란색, 하단은 녹색).
    
    ## 추가 정보
    
    * [고급 방향 조정](../advanced_config/advanced_flight_controller_orientation_leveling.md) (고급 사용자용).
    * [QGroundControl 사용자 안내서 > 센서](https://docs.qgroundcontrol.com/en/SetupView/sensors_px4.html#level-horizon)
    * [PX4 설치 동영상 "각가속 센서"- @ 1분 14초](https://youtu.be/91VGmdSlbo4?t=1m14s)(유튜브)