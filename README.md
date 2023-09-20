# ArmoredCore6-Analysis

# 목차
* [1. 이동](#1-이동)

# 1. 이동
## 기본 이동

[![기본 이동](https://img.youtube.com/vi/h9uPb_5z39U/0.jpg)](https://www.youtube.com/watch?v=h9uPb_5z39U)

1. 다리를 좌우 교체하며 지면을 이동한다.
2. 카메라가 위아래로 아주 미세하게 흔들린다.
3. 현재 플레이어가 바라보는 방향과 다른 방향으로 이동 시 플레이어가 이동 방향으로 회전한다.

## 부스트

[![부스트](https://img.youtube.com/vi/3IFr1yZHeDk/0.jpg)](https://www.youtube.com/watch?v=3IFr1yZHeDk)

1. 다리를 지면에 붙인채 고속 이동한다.
2. 방향을 전환하거나 멈출 시 반동으로 일정 거리를 미끄러지듯 이동한다.
3. 반대 방향으로 전환 시 잠깐 이동을 정지한 후 큰 동작으로 회전한다.
4. 카메라가 이동 방향의 반대 방향으로 미세하기 밀려나는 효과가 있다.

## 점프

[![점프](https://img.youtube.com/vi/sT1iMvwCdTc/0.jpg)](https://www.youtube.com/watch?v=sT1iMvwCdTc)

1. 짧은 시간 몸을 웅크리고 플레이어가 바라보는 방향으로 고속 상승한다.
2. 부스트 on 상태에서 점프할 경우 공중에서도 부스트 상태가 유지되며 착지할 때 반동으로 일정 거리를 미끄러지듯 이동한다.   
착지한 후 다음 동작까지 딜레이가 생기지 않고 자연스럽게 이동한다.
3. 부스트 off 상태에서 착지 시 착지한 자리에 일정 시간 멈추며 다음 동작까지 딜레이가 생긴다.
4. 착지하기 전 방향을 전환해도 처음 점프한 방향의 반동을 받는다.
5. 카메라가 점프 방향의 반대 방향으로 크게 밀려나는 효과가 있다.

## 퀵 부스트

[![퀵 부스트](https://img.youtube.com/vi/G_jCcrPLllA/0.jpg)](https://www.youtube.com/watch?v=G_jCcrPLllA)

1. 플레이어가 바라보는 방향으로 순간적으로 크게 이동한다.
2. EN 에너지를 소비한다.
3. 사용 후엔 부스트 on 상태가 된다.
4. 미세하게 공중으로 상승한다.
6. 카메라가 퀵 부스트 방향의 반대 방향으로 매우 크게 밀려나는 효과가 있다.

## 상승

[![상승](https://img.youtube.com/vi/hKJArCeoC0g/0.jpg)](https://www.youtube.com/watch?v=hKJArCeoC0g)

1. 점프를 유지할 경우 지속적으로 EN 에너지를 소비하여 상승한다.
2. 부스트 on 상태일 경우 공중에서 더 고속으로 이동한다.
3. 상승 중엔 이동과 퀵 부스트를 사용할 수 있다.
4. 이동이 없으면 추락할 때 가속도가 생기고, 공중에서 이동할 경우 천천히 활강하며 추락한다.

## 어썰트 부스트

[![어썰트 부스트](https://img.youtube.com/vi/TQyDlCJ5mxI/0.jpg)](https://www.youtube.com/watch?v=TQyDlCJ5mxI)

1. 현재 플레이어가 바라보는 방향으로 고속 이동.
2. 토글 방식으로 on/off.
3. on 상태에서 좌우 이동 시 해당 방향으로 대쉬, 후방 이동 시 off 상태로 전환.
4. 어썰트 부스트 중 재발동 시 가속도 비례한 킥 공격을 시전하고 off 상태로 전환.
