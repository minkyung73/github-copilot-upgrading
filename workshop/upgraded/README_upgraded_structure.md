# upgraded 디렉터리 구조 설명

이 디렉터리는 legacy(레거시) 폴더의 전체 파일 및 폴더 구조를 복사하여 생성되었습니다. 각 파일과 폴더는 다음과 같은 역할을 합니다:

- MANIFEST.in, README.rst, distribute-0.6.10.tar.gz, distribute_setup.py, setup.py: 프로젝트 메타 정보 및 설치 관련 파일
- docs/: 프로젝트 문서 디렉터리
- guachi/: 주요 Python 패키지 소스 코드
  - __init__.py, config.py, database.py: 패키지 초기화 및 주요 모듈
  - tests/: 단위 테스트 코드
- guachi.egg-info/: 패키지 메타데이터 정보
- upgraded/: 레거시 코드를 최신화하거나 실험적으로 변경할 때 사용하는 작업 디렉터리(현재 위치)

이 디렉터리는 레거시 코드를 최신 Python 환경으로 포팅하거나 실험하는 데 사용됩니다. 각 파일은 원본과 동일한 이름과 구조로 복사되어 있으며, 실제 코드 변경은 이 디렉터리에서 진행할 수 있습니다.
