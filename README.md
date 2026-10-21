<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=3693D1FF&section=header&reversal=false&text=Kim+Joonseok&textBg=false&fontSize=60&fontAlign=50&fontAlignY=35&animation=fadeIn&rotate=0&strokeWidth=0&descSize=20&descAlign=50&descAlignY=60&fontColor=FFFFFF" />
</p>

<div align="center"> ☁️ Cloud/Infra Engineering ☁️ </div>


## Introduce
**세밀한 관측을 통해 안정적인 인프라를 구축, 운영하는 Cloud/Infra Enginner를 지향합니다.**  
단순히 동작하는 인프라를 구축하는 것을 넘어, 관측 데이터를 통해서 인프라 구성을 동적으로 수정하여 요구사항에 부합하는 인프라를 구축, 운영하고자 합니다.
어플리케이션에 대한 이해를 바탕으로 AWS, OpenStack, CI/CD등을 기반으로한 안정적인 인프라 구축을 목표로 하며, LLM에 대한 이해를 바탕으로 LLM 추론/서빙 최적화로 확장하고자합니다.

  
## Education & Certification
- 숭실대학교 소프트웨어학부 | 2026.03 ~
- 숭실대학교 Co-op 클라우드 트랙 쿠버네티스 과정 | 2025.12 ~ 2026.01
- Comento 직무 부트캠프 리눅스 기반 Web - WAS - DB 서버 구축 과정 | 2026.06 ~ 2026.07
- 잇다 취업 동아리 중심 멘토링 | 2026.09 ~ 2026.10
- 정보처리기사(Engineer Information Processing) | 2026.09

  
## Experience
- 2026 Open UP 오픈소스 컨트리뷰션 아카데미 OpenStack & Kubernetes 트랙 | 2026.04 ~ 2026.10
- 2026 SoftBank Hackathon | 2026.10

  
## Project
- ### [teamBuildAI](https://github.com/LyleKim/teambuildAI)  

  공모전, 해커톤 참가를 위한 AI 기반 팀빌딩 매칭 플랫폼
    
  Technical Highlights
  - Restful API
  - 로직,뷰 분리/DTO/CORS/예외 처리 검토
  - Swagger, OpenAPI 문서화
  - 서브 에이전트 기반 병렬 처리 및 자가 검토 구성의 개발

- ### [qemu-exporter](https://github.com/LyleKim/qemu-exporter)

  openStack-Helm기반 OpenStack에서 배포된 VM의 PSI 지표를 Prometheus로 노출시키는 관측기

  Technical Highlights  
  - libvirt 파드 -> QEMU 프로세스 동작에 대한 이해
  - libvirt API를 통한 QEMU 프로세스의 PID 파싱
  - QEMU 프로세스 PID를 사용하여 QEMU 프로세스별 cgroup의 도메인 스레드 탐색(PSI 파싱을 위함)
  - Nova 메타데이터(인스턴스 이름, 인스턴스 타입 등)와 VM 별 PSI 지표를 하나로 묶어서 Prometheus로 노출
  - webhook, Nova API를 활용한 VM 라이브 마이그레이션
