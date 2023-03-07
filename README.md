# EurotruckAutonomousDriving
유로트럭 자율주행 플러그인 개발

방법: 유로트럭 게임에서 자율주행 플러그인을 만들려면, 우선 게임의 API를 이용해서 자동차를 제어하는 코드를 작성해야 합니다. 게임 API는 게임 제작사에서 제공하며, 일반적으로 C++ 또는 C#로 작성됩니다.

자율주행 알고리즘은 여러 가지가 있지만, 현재 가장 많이 사용되는 알고리즘은 딥러닝을 기반으로 한 강화학습 알고리즘입니다. 따라서, 자율주행 플러그인을 개발하려면 딥러닝 프레임워크인 TensorFlow, PyTorch 등을 이용하여 강화학습 알고리즘을 구현해야 합니다.

또한, 게임에서 자동차의 상태를 감지하고, 주행을 제어하는 기능도 필요합니다. 이를 위해서는 게임의 스크립트 기능을 이용하여 필요한 정보를 추출하고, 제어 신호를 보내야 합니다. 게임에서 제공하는 스크립트 기능을 이용할 수도 있지만, 외부 스크립트 언어를 이용하여 제어할 수도 있습니다.

마지막으로, 자율주행 플러그인을 개발하기 위해서는 프로그래밍 언어 및 딥러닝 지식 등에 대한 기초적인 이해가 필요합니다. 게임 개발과 머신러닝에 대한 지식을 함께 갖춘 전문가의 도움이 필요할 수도 있습니다.

 SCS Software 공식 사이트에서 제공하는 API 및 모딩 도구 페이지입니다.

EuroTruck Simulator 2 Modding 도구: https://modding.scssoft.com/wiki/Documentation/Tools/Euro_Truck_Simulator_2_Modding_Tools
또한, EuroTruck Simulator 2와 American Truck Simulator 게임 데이터를 분석할 수 있는 여러 서드파티 라이브러리와 도구들도 있습니다. 예를 들어, ETS2 Telemetry SDK, ETS2 Telemetry Web Server, ETS2 Local Radio 등이 있습니다. 이러한 도구와 라이브러리를 사용하여 게임 데이터를 읽고 처리할 수 있습니다.



API 연결: EuroTruck Simulator 2와 American Truck Simulator 게임에서 자동차 운전 데이터를 가져올 수 있는 API를 사용할 수 있습니다. 이를 위해서는 API에 연결하고 API로부터 데이터를 가져오는 방법을 알아야 합니다.

데이터 수집: API로부터 수집한 데이터를 사용하여 자율주행 알고리즘을 구현해야 합니다. 수집해야 하는 데이터는 자동차의 위치, 속도, 방향, 가속도, 주행 경로 등입니다.

자율주행 알고리즘 개발: 수집한 데이터를 사용하여 자율주행 알고리즘을 개발해야 합니다. 이 알고리즘은 주행 경로를 계산하고, 다른 자동차와 충돌을 피하며, 효율적으로 운전해야 합니다.

제어 시스템 구현: 자율주행 알고리즘을 사용하여 자동차를 제어해야 합니다. 이를 위해서는 자동차 제어 시스템을 구현해야 하며, 이를 통해 자동차의 속도, 핸들 등을 조작할 수 있습니다.

시뮬레이션: 모든 코드를 작성한 후에는 시뮬레이션을 실행하여 실제로 자율주행이 잘 작동하는지 확인해야 합니다. 시뮬레이션을 실행하면서 버그를 수정하고, 성능을 향상시킬 수 있습니다.


EuroTruck Simulator 2와 American Truck Simulator 게임에서 API를 사용하려면 다음과 같은 단계를 따라야 합니다.

게임 설정 변경: API를 사용하려면 EuroTruck Simulator 2 또는 American Truck Simulator 게임 설정에서 "Telemetry Server" 옵션을 활성화해야 합니다.

Telemetry Server 시작: Telemetry Server는 게임에서 API로 데이터를 전송하는 역할을 합니다. Telemetry Server를 시작하려면 다음 경로에서 "bin/win_x64/plugins/telemetry" 디렉토리에 있는 "telemetry_server_x64.exe" 파일을 실행합니다.

API 연결: API를 사용하려면 클라이언트 애플리케이션에서 Telemetry Server에 연결해야 합니다. 이를 위해서는 클라이언트 애플리케이션에서 Telemetry Server의 IP 주소와 포트 번호를 지정해야 합니다.

데이터 수집: API를 사용하여 수집할 수 있는 데이터는 다양하지만, 일반적으로 자동차의 위치, 속도, 방향, 가속도, RPM, 기어, 연료량, 엔진 온도 등이 포함됩니다. 이러한 데이터는 JSON 형식으로 제공됩니다.

API 문서 확인: EuroTruck Simulator 2와 American Truck Simulator API의 자세한 설명은 SCS Software의 공식 문서에서 확인할 수 있습니다. https://github.com/SCSSoftware/Telemetry-SDK

이러한 단계를 따라 API를 사용하여 EuroTruck Simulator 2와 American Truck Simulator 게임 데이터를 가져올 수 있습니다.
