## Install

하모니카OS 데스크톱 환경을 구성하는 메타 패키지

- 하모니카OS 전체 기능을 포함한 패키지 : hamonikr-desktop-environment
- 하모니카OS 기본 환경을 구성하는 패키지 : hamonikr-desktop-base

### HamoniKR (>=5.0)

```
wget -qO- https://update.hamonikr.org/add-update-repo.apt | sudo -E bash -

sudo apt-get install hamonikr-desktop-environment

```

### Ubuntu (>=20.04)

시나몬 데스크톱 매니저를 사용하지 않는 경우에는 다음과 같이 먼저 시나몬 데스크톱을 설치해야 합니다.

```
wget -qO- https://update.hamonikr.org/add-update-repo.apt | sudo -E bash -

# 시나몬 환경 설치
sudo apt-get install cinnamon-desktop-environment

# 하모니카OS 데스크톱 환경 설치
sudo apt-get install hamonikr-desktop-environment

```
