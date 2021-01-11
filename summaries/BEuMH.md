# Building Evacuation using Microsoft HoloLens
James Stingall, Sri Teja Bodempudi, Sharad Sharma, David Scribner, Jock Grynovicki, Peter Grazaitis, SEDE 2018

## Summary
- 사람들은 시간적 제약 때문에 실시간 대피 훈련에 참가하지 못할 수 있음
- 2D 평면도 이미지는 대피 경로를 파악에 도움을 주는 것에 한계가 있음
- Microsoft HoloLens를 통해 사용자는 건물을 더 잘 볼 수 있고 대피하는 동안 건물 밖으로 나가는 길을 좀 더 쉽게 찾을 수 있음
- 논문의 기여도
    - 3D로 된 빌딩을 시각적으로 표현하기 위해 HoloLens용 프로그램 개발
    - 건물 내 내 자신의 위치 및 출구 확인 가능
    - 출구로 향하는 안전 경로 계산(음성 명령 작업 가능)
    - 대피를 위한 HoloLens 애플리케이션의 유효성을 검증한 평과결과

## System Architecture
- HoloLens에는 메인 카메라와 두 개의 센서가 있음
    - 음성 명령과 제스처 인식을 위한 각각의 센서
- HoloLens의 단점은 GPS가 없다는 점
- 하지만 이미지 마커(2D 평면도)를 인식할 때 위치를 파악하여 단점을 보완함
- 평면도에 녹색 화살표로 표시하여 출구를 향한 경로를 알려줌

## Pilot Study
- 10명에게 조사함(80% 남성, 20% 여성)
- 동기, 사용성, 교육 및 훈련 효과, AR 애플리케이션 플랫폼의 적합성에 대한 참가자의 인식을 측정함
- 60%가 HoloLens, 40%는 태블릿이 낫다고 응답했음
- 40%가 태블릿을 선호하는 이유는 제스처를 사용하는 HoloLens를 태블릿에 비해 어렵다고 생각함
- 100%의 참가자들은 복잡한 구조를 가진 정보를 가지고 있지 않은 건물에서 유용할 것이라 생각함
- 90%의 참가자들은 HoloLens를 이용한 앱이 실시간 대피에 도움이 될 것이라 생각함
- 90%의 참가자들은 해당 애플리케이션이 2D 평면도를 이용한 대피 계획의 대체 수단으로 사용될 수 있을 것이라 생각함

## Conclusion
- HoloLens와 같은 AR 기술은 비상시에 다른 사람들을 대피시키기 위해 채택되어야함
