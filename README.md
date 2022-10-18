## Install

하모니카OS 데스크톱 환경을 구성하는 메타 패키지로 아래 2가지가 있습니다.

- 하모니카OS 전체 기능을 포함한 패키지 : `hamonikr-desktop-environment`
- 하모니카OS 기본 환경을 구성하는 패키지 : `hamonikr-desktop-base`

그 외 추가적으로 아래의 패키지가 제공됩니다.

- 하모니카OS 개발팀에서 제공하는 고급 사용자를 위한 패키지 : `hamonikr-desktop-full`

    `asbru-cm, boot-select, convert-svg, mainline, hamonikr-ff, hamonikr-checksum, live-usb-creator, systemback, qt-fsarchiver`

- 하모니카OS 환경에서 소프트웨어를 개발하는 개발자를 위한 추가 패키지 : `hamonikr-desktop-extra`

    `hamonikr-cli-tools, filezilla, slack-desktop, zoom, gimp, inkscape, gh, github-desktop 등`

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
