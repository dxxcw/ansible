# Ansible Practice

Ansible 기초 실습 코드 저장소입니다.  
인프라 자동화 도구인 Ansible의 주요 기능을 실습하고 학습한 내용을 정리합니다.

## 📚 학습 내용 요약

- 인벤토리 구성 (INI, YAML 형식)
- 패키지 설치 및 서비스 제어
- block / rescue / always 구조 이해
- 변수 활용 및 Jinja2 템플릿 문법
- 시스템 명령 실행 (command, shell)
- 디버깅 및 출력 확인 (debug)

## 📁 디렉토리 구조

예시:

    .
    ├── inventory        # 인벤토리 파일
    ├── playbook.yml     # 메인 플레이북
    └── README.md        # 설명 문서

## ▶️ 실행 방법

Ansible이 설치된 환경에서 다음 명령어로 실행합니다:

    ansible-playbook -i inventory playbook.yml

※ SSH 접속이 가능한 대상 서버가 구성되어 있어야 합니다.

---

본 저장소는 Ansible 학습 목적의 실습 예제 모음입니다.
필요 시 단계별로 확장 가능합니다.
