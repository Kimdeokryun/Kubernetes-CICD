# Kubernetes-CICD

Kubernetes와 Jenkins 를 사용한 CICD 학습

# 

![Alt text](image.png)


참고자료: 컨테이너 인프라 환경 구축을 위한 쿠버네티스/도커

활용법: https://github.com/sysnet4admin/_Book_k8sInfra

#

1. 가상화 인프라 환경 구성 

VirtualBox &  Vagrant - CentOS(Linux)

베이그런트는 사용자의 요구에 맞게 시스템 자원을 할당, 배치, 배포해 두었다가 필요할 때 시스템을 사용할 수 있는 상태로 만들어 줍니다.

2. 컨테이너 다루기

Kubernetes & Docker (CE)

쿠버네티스(Kubernetes)는 다수의 컨테이너(이 책에서는 도커를 사용)를 관리하는 데 사용합니다. 컨테이너의 자동 배포와 배포된 컨테이너에 대한 동작 보증, 부하에 따른 동적 확장 등의 기능을 제공합니다.

도커(Docker)는 컨테이너 환경에서 독립적으로 애플리케이션을 실행할 수 있도록 컨테이너를 만들고 관리하는 것을 도와주는 컨테이너 도구입니다.

3. CI CD

Jenkins

젠킨스(Jenkins)는 지속적 통합(CI, Continuous Integration)과 지속적 배포(CD, Continuous Deployment)를 지원합니다.

지속적 통합과 지속적 배포는 개발한 프로그램의 빌드, 테스트, 패키지화, 배포 단계를 모두 자동화해 개발 단계를 표준화합니다.

4. 컨테이너 인프라 환경 관리하기

Prometheus & Grafana

프로메테우스(Prometheus)와 그라파나(Grafana)는 모니터링을 위한 도구입니다. 프로메테우스는 상태 데이터를 수집하고, 그라파나는 프로메테우스로 수집한 데이터를 관리자가 보기 좋게 시각화합니다. 컨테이너 인프라 환경에서는 많은 종류의 소규모 기능이 각각 나누어 개발되기 때문에 중앙 모니터링이 필요합니다.

#


