## hamonikr-meta

하모니카OS 데스크톱 환경을 구성하는 메타 패키지로 아래와 같이 제공됩니다.

- 하모니카OS 기본 환경을 구성하는 패키지 : `hamonikr-desktop-minimal`
- 하모니카OS 전체 기능을 포함한 패키지 : `hamonikr-desktop-environment`


그 외 추가적으로 아래의 패키지가 제공됩니다.

- 하모니카OS 개발팀에서 제공하는 고급 사용자를 위한 패키지 : `hamonikr-desktop-full`

    `asbru-cm, boot-select, convert-svg, mainline, hamonikr-ff, hamonikr-checksum, live-usb-creator, systemback, qt-fsarchiver`

- 하모니카OS 환경에서 소프트웨어를 개발하는 개발자를 위한 추가 패키지 : `hamonikr-desktop-extra`

    `hamonikr-cli-tools, filezilla, slack-desktop, zoom, gimp, inkscape, gh, github-desktop 등`


## Ubuntu (20.04), LMDE 5, Debian (bullseye) 에서 하모니카 데스크톱 환경을 사용하는법

우분투 및 데비안 계열에서 다음과 같이 하모니카 환경을 사용할 수 있습니다.

```
wget -qO- https://update.hamonikr.org/add-update-repo.apt | sudo -E bash -

sudo apt-get install hamonikr-desktop-environment

```


## HamoniKR 5.0 사용자는 다음과 같이 저장소를 추가하고 사용할 수 있습니다.
```
wget -qO- https://update.hamonikr.org/add-update-repo.apt | sudo -E bash -

sudo apt-get install hamonikr-desktop-environment

```




