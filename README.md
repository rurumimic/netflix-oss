# Netflix Open Source Software

Netflix [Open Source Software](https://netflix.github.io/)  
Netflix [GitHub](https://github.com/Netflix)

## 빅 데이터

데이터를 활용하기 위한 도구와 서비스

넷플릭스는 데이터를 귀중하게 생각한다. 고객에게 뛰어난 서비스를 제공할 수 있는 이유는, 알고리즘과 분석을 편리하게 만들어주는 풍부한 빅데이터 기술 생태계를 가지고 있기 때문이다. Hadoop, Hive, Pig, Parquet, Presto, Spark처럼 많은 오픈 소스 기술을 사용하고 기여한다. 또한, 몇가지 도구와 서비스를 만들어 오픈 소스로 공개했다. Genie는 하둡과 같은 데이터 처리 프레임워크를 위한 REST 기반 추상화 서비스다. Invisio는 하둡 작업 및 클러스터 성능에 대해 자세한 통찰력을 제공한다. Lipstick은 피그 작업의 워크플로우를 맵시 있게 보여준다. Aegisthus는 다운 스트림 분석 처리를 위해 카산드라에서 데이터를 대량으로 추상화할 수 있다.

## 빌드 및 배포 도구

데스크탑에서 클라우드로 코드 가져오기

Nebula는 Gradle 플러그인 오픈 소스다. 개발자는 간단하게 빌드, 테스트, 배포 사용할 수 있다. 표준화된 플러그인 개발 덕분에 구성이 쉽고 모듈 빌드가 쉽다.

AWS로 쉽게 빌드 결과물을 옮길 수 있는 도구가 필요했다. 넷플릭스에선 수만 개의 인스턴스가 동작하고 있다. 인스턴스는 Aminator로 만든 이미지 위에서 작동 중이다. Spinnaker는 AMI로 만든 패키지 이미지를 AWS로 지속적으로 배포하는 플래폼이다. 높은 속도와 자신감으로 소프트웨어 변화를 쉽게 배포한다.
