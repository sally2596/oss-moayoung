# <div align="center">oss-moayoung</div><br>

<br>

<div align="center">

![license](https://img.shields.io/crates/l/ap?color=white)
![contributors](https://img.shields.io/github/contributors/daaaayeah/oss-moayoung?color=white)
![last-commit](https://img.shields.io/github/last-commit/daaaayeah/oss-moayoung?color=white)

</div>

<br>

![main](https://user-images.githubusercontent.com/52737532/132761342-cfca0e85-72b9-4242-ae27-93e0e8813b04.PNG)

<br>

Video calling service that encompasses everyone (hereinafter referred to as "moayoung") is a web-based service that anyone can conveniently use regardless of vision or hearing impairment. moayoung's users can participate in video calls only by accessing the website without a separate software installation process, and various convenience features can relieve visual, hearing, and functional discomfort.

<br>

## Features

- Detecting that it's out of frame
- Zoom in on the speaker's mouth
- Automatic subtitle generation
- Participant notification.

<br>

## Using moayoung

<a href="https://moayoung-call.web.app/">🏠 Go to moayoung !</a>

<a href="https://github.com/daaaayeah/oss-moayoung/wiki">🔍 Moayoung wiki</a>

<br>

## Browser support

<img src="https://img.shields.io/badge/chrome-4285F4?style=flat-square&logo=Google Chrome&logoColor=white" width="100" height="32"/>
<img src="https://img.shields.io/badge/Microsoft Edge-0078D7?style=flat-square&logo=Microsoft Edge&logoColor=white" width="150" height="32"/>

<br>

## Installation

### Prerequisites

- Git
- npm
- Node.js
- grunt

<br>

### Configuration

<br>

- Clone code and dependencies

```
git clone https://github.com/daaaayeah/oss-moayoung.git
cd oss-moayoung
```

```
cd oss-moayoung/homepage
yarn
```

```
cd ../meeting
npm install
```

- Create configuration and customize files

Linux

```
cp src/config.tmp.json src/config.json
cp src/assets/sass/_custom.tmp.scss src/assets/sass/_custom.scss
```

Windows

```
copy src\config.tmp.json src\config.json
copy src\assets\sass\_custom.tmp.scss src\assets\sass\_custom.scss
```

- Deploy

```
//meeting
grunt deploy
```

<br>

## License

<a  href="https://github.com/daaaayeah/oss-moayoung/blob/main/LICENSE">Apache License 2.0</a>
