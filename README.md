# Rolland-Garros v.2 iOS

_Rolland-Garros_ is the official iOS application of the Rolland-Garros tournament.

# Demo-Preview

Some demo will be here...

## Contents

- [Rolland-Garros v.2 iOS](#rolland-garros-v2-ios)
- [Demo-Preview](#demo-preview)
- [Contents](#contents)
- [Resources](#resources)

# Installation
[(Back to contents)](#contents)

To use this project, first [set your connection to github with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

Сlone the repo on your device:

```
git clone https://github.com/netcosports/Roland_Garros_v2_iOS.git
```

Make sure thay you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install [Homebrew](https://brew.sh/):

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install [bundler](https://bundler.io/):
```
gem install bundler:2.2.16
```

Navigate to project's folder in terminal and for gems installing run:

```
bundle install
``` 

Make sure that you have access for all necessary github repositories [here](https://github.com/netcosports/Roland_Garros_v2_iOS/blob/development/Podfile).

For installing pods run:

```
bundle exec pods install
```

For updating pod run:

```
bundle exec pod update
```

For installing vpn client go [here](https://vpn.cedoni.com/). Ask your manager for your credentials, open `AnyConnect` section, download Cisco AnyConnect Secure Mobility Client and install it.

# Resources
[(Back to contents)](#contents)

- [API](https://docs.google.com/spreadsheets/d/1kIEJcooh3hIipZQdds9s0v1ihHpiYybnfgrjBJ4-qEA/edit#gid=0)
- [Confluence](https://fedfraten.atlassian.net/wiki/spaces/RGApp/overview)
- [Jira](https://fedfraten.atlassian.net/secure/RapidBoard.jspa?rapidView=22)
- [Localization](https://docs.google.com/spreadsheets/d/13NK4l4XxQUbYk7R0-F52k8w7jgC_So1vzCEOGHQ9x1M/edit#gid=0)
- [Sketch](https://drive.google.com/drive/u/0/folders/1qUIibjueEqzBc8haAjeojwLGbzCRMMD7)
- [Xiti](https://drive.google.com/drive/folders/1Fs-QAQSGTOEJe4CQIfQqlMAah8w8FDe8)
