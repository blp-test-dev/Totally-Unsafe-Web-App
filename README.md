# PyGoat
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-9-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

intentionally vuln web Application Security in django.
our roadmap build intentionally vuln web Application in django. The Vulnerability can based on OWASP top ten
<br>

Table of Contents
=================

* [pygoat](#pygoat)
   * [Installation](#installation)
      * [From Sources](#from-sources)
      * [Docker Container](#docker-container)
      * [Installation Video](#installation-video)
   * [Uninstallation](#uninstallation)
   * [Solutions](/Solutions/solution.md)
   * [For Developers](/docs/dev_guide.md)

## Installation

### From Sources

To setup the project on your local machine:
<br>

First, Clone the repository using GitHub website or git in Terminal
```
  git clone https://github.com/adeyosemanputra/pygoat.git
  ### To Download a specific branch
  git clone -b <branch_name> https://github.com/adeyosemanputra/pygoat.git
```

#### Method 1

1. Install all app and python requirements using installer file - `bash installer.sh`
2. Apply the migrations `python3 manage.py migrate`.<br>
3. Finally, run the development server `python3 manage.py runserver`.<br>
4. The project will be available at <http://127.0.0.1:8000> 

#### Method 2

1. Install python3 requirements `pip install -r requirements.txt`.<br> 
2. Apply the migrations `python3 manage.py migrate`.<br>
3. Finally, run the development server `python3 manage.py runserver`.<br>
4. The project will be available at <http://127.0.0.1:8000> 

#### Method 3

1. Install all app and python requirements using `setup.py` file - `pip3 install .`
2. Apply the migrations `python3 manage.py migrate`.<br>
3. Finally, run the development server `python3 manage.py runserver`.<br>
4. The project will be available at <http://127.0.0.1:8000> 

### Docker Container
1. Install [Docker](https://www.docker.com)
2. Run `docker pull pygoat/pygoat` or `docker pull pygoat/pygoat:latest`
3. Run `docker run --rm -p 8000:8000 pygoat/pygoat:latest`
4. Browse to <http://127.0.0.1:8000> 
5. Remove existing image using `docker image rm pygoat/pygoat` and pull again incase of any error

### From Docker-Compose 
1. Install [Docker](https://www.docker.com)
2. Run `docker-compose up` or `docker-compose up -d`

### Build Docker Image and Run
1. Clone the repository  &ensp; `git clone https://github.com/adeyosemanputra/pygoat.git` 
2. Build the docker image from Dockerfile using &ensp; `docker build -f Dockerfile -t pygoat .`
3. Run the docker image &ensp;`docker run --rm -p 8000:8000 pygoat:latest`
4. Browse to <http://127.0.0.1:8000> or <http://0.0.0.0:8000> 

### Installation video 

1. From Source using `installer.sh`
 - [Installing PyGoat from Source](https://www.youtube.com/watch?v=7bYBJXG3FRQ)
2. Without using `installer.sh`
 - [![](http://img.youtube.com/vi/rfzQiMeiwso/0.jpg)](http://www.youtube.com/watch?v=rfzQiMeiwso "Installation Pygoat")

## Uninstallation

### On Debian/Ubuntu Based Systems
- On Debian/Ubuntu based systems, you can use the `uninstaller.sh` script to uninstall `pygoat` along with all it's dependencies.
- To uninstall `pygoat`, simply run:
```bash
$ bash ./uninstaller.sh
```

### On Other Systems
- On other systems, you can use the `uninstaller.py` script to uninstall `pygoat` along with all it's dependencies
- To uninstall `pygoat`, simply run:
```bash
$ python3 uninstaller.py
```

## Solutions 
<a href="/Solutions/solution.md">Solutions to all challenges</a>

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/pwned-17"><img src="https://avatars.githubusercontent.com/u/61360833?v=4?s=100" width="100px;" alt=""/><br /><sub><b>pwned-17</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=pwned-17" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/prince-7"><img src="https://avatars.githubusercontent.com/u/53997924?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Aman Singh</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=prince-7" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/adeyosemanputra"><img src="https://avatars.githubusercontent.com/u/24958168?v=4?s=100" width="100px;" alt=""/><br /><sub><b>adeyosemanputra</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=adeyosemanputra" title="Code">💻</a> <a href="https://github.com/adeyosemanputra/pygoat/commits?author=adeyosemanputra" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/gaurav618618"><img src="https://avatars.githubusercontent.com/u/29380890?v=4?s=100" width="100px;" alt=""/><br /><sub><b>gaurav618618</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=gaurav618618" title="Code">💻</a> <a href="https://github.com/adeyosemanputra/pygoat/commits?author=gaurav618618" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/kUSHAL0601"><img src="https://avatars.githubusercontent.com/u/29600964?v=4?s=100" width="100px;" alt=""/><br /><sub><b>MajAK</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=kUSHAL0601" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/JustinDPerkins"><img src="https://avatars.githubusercontent.com/u/60413733?v=4?s=100" width="100px;" alt=""/><br /><sub><b>JustinPerkins</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=JustinDPerkins" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Hkakashi"><img src="https://avatars.githubusercontent.com/u/43193113?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Liu Peng</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=Hkakashi" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/RupakBiswas-2304"><img src="https://avatars.githubusercontent.com/u/75058161?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Metaphor</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=RupakBiswas-2304" title="Code">💻</a></td>
    <td align="center"><a href="https://whokilleddb.github.io"><img src="https://avatars.githubusercontent.com/u/56482137?v=4?s=100" width="100px;" alt=""/><br /><sub><b>whokilleddb</b></sub></a><br /><a href="https://github.com/adeyosemanputra/pygoat/commits?author=whokilleddb" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!



Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Egestas maecenas pharetra convallis posuere morbi leo urna. Urna nec tincidunt praesent semper feugiat. Ut faucibus pulvinar elementum integer. Consectetur adipiscing elit duis tristique sollicitudin nibh sit. Duis ut diam quam nulla porttitor. Vitae purus faucibus ornare suspendisse sed nisi lacus sed viverra. Consectetur adipiscing elit pellentesque habitant morbi tristique senectus et netus. Egestas erat imperdiet sed euismod nisi. Quis commodo odio aenean sed adipiscing diam donec adipiscing. Tortor aliquam nulla facilisi cras fermentum odio. Scelerisque purus semper eget duis at. Aliquam etiam erat velit scelerisque in dictum. In egestas erat imperdiet sed euismod. Ridiculus mus mauris vitae ultricies. Volutpat ac tincidunt vitae semper quis. Leo integer malesuada nunc vel risus commodo.

Orci ac auctor augue mauris augue neque gravida. Urna condimentum mattis pellentesque id nibh tortor id. Ullamcorper dignissim cras tincidunt lobortis feugiat vivamus at. Lorem donec massa sapien faucibus et. Diam vulputate ut pharetra sit amet aliquam id. Id velit ut tortor pretium. Enim neque volutpat ac tincidunt vitae semper quis lectus. Scelerisque viverra mauris in aliquam sem fringilla ut. Turpis massa sed elementum tempus egestas. Sem viverra aliquet eget sit amet tellus. Sed vulputate mi sit amet mauris commodo quis imperdiet. Pellentesque eu tincidunt tortor aliquam nulla facilisi.

Vel pretium lectus quam id leo in vitae. Amet tellus cras adipiscing enim. Gravida in fermentum et sollicitudin ac. Lorem dolor sed viverra ipsum nunc aliquet. Eleifend quam adipiscing vitae proin. Feugiat pretium nibh ipsum consequat nisl vel pretium lectus quam. Tellus mauris a diam maecenas sed. Diam phasellus vestibulum lorem sed. Placerat in egestas erat imperdiet sed euismod. Gravida rutrum quisque non tellus orci ac auctor. Maecenas sed enim ut sem viverra aliquet. Sociis natoque penatibus et magnis dis parturient. Lacinia quis vel eros donec ac odio tempor.

At tempor commodo ullamcorper a lacus. A pellentesque sit amet porttitor eget dolor morbi non arcu. Magna etiam tempor orci eu lobortis elementum nibh tellus. Tristique et egestas quis ipsum suspendisse ultrices gravida. Nibh tortor id aliquet lectus proin nibh. Metus dictum at tempor commodo ullamcorper a lacus vestibulum sed. Ac tortor dignissim convallis aenean. Leo urna molestie at elementum eu facilisis. Auctor urna nunc id cursus metus. Risus quis varius quam quisque. Feugiat nibh sed pulvinar proin. Vitae turpis massa sed elementum tempus egestas sed sed. Pellentesque habitant morbi tristique senectus et netus et malesuada. Etiam erat velit scelerisque in dictum non consectetur. Sed faucibus turpis in eu mi bibendum neque egestas.

Velit scelerisque in dictum non consectetur. Senectus et netus et malesuada. Augue lacus viverra vitae congue. Nisi porta lorem mollis aliquam ut. Enim praesent elementum facilisis leo. Ridiculus mus mauris vitae ultricies leo integer malesuada nunc vel. Turpis in eu mi bibendum. Varius sit amet mattis vulputate enim nulla aliquet porttitor lacus. Scelerisque eu ultrices vitae auctor eu augue ut lectus. Lorem dolor sed viverra ipsum nunc aliquet bibendum. Scelerisque in dictum non consectetur a erat nam. Praesent semper feugiat nibh sed pulvinar proin gravida. Id aliquet lectus proin nibh nisl condimentum id. Ultrices vitae auctor eu augue ut lectus arcu bibendum at.