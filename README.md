
<h1 align="center">
  <br>
  <a href="https://github.com/s0md3v/Photon"><img src="https://image.ibb.co/h5OZAK/photonsmall.png" alt="Photon"></a>
  <br>
  Photon
  <br>
</h1>

<h4 align="center">Incredibly fast crawler designed for OSINT.</h4>

<p align="center">
  <a href="https://github.com/s0md3v/Photon/releases">
    <img src="https://img.shields.io/github/release/s0md3v/Photon.svg">
  </a>
  <a href="https://pypi.org/project/photon/">
    <img src="https://img.shields.io/badge/pypi-@photon-red.svg?style=style=flat-square"
         alt="pypi">
  </a>
  <a href="https://github.com/s0md3v/Photon/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues-closed-raw/s0md3v/Photon.svg">
  </a>
  <a href="https://travis-ci.com/s0md3v/Photon">
    <img src="https://img.shields.io/travis/com/s0md3v/Photon.svg">
  </a>
</p>

![demo](https://image.ibb.co/kQSUcz/demo.png)

<p align="center">
  <a href="https://github.com/s0md3v/Photon/wiki">Photon Wiki</a> •
  <a href="https://github.com/s0md3v/Photon/wiki/Usage">How To Use</a> •
  <a href="https://github.com/s0md3v/Photon/wiki/Compatibility-&-Dependencies">Compatibility</a> •
  <a href="https://github.com/s0md3v/Photon/wiki/Photon-Library">Photon Library</a> •
  <a href="#contribution--license">Contribution</a> •
  <a href="https://github.com/s0md3v/Photon/projects/1">Roadmap</a>
</p>

### Key Features

#### Data Extraction
Photon can extract the following data while crawling:

- URLs (in-scope & out-of-scope)
- URLs with parameters (`example.com/gallery.php?id=2`)
- Intel (emails, social media accounts, amazon buckets etc.)
- Files (pdf, png, xml etc.)
- Secret keys (auth/API keys & hashes)
- JavaScript files & Endpoints present in them
- Strings matching custom regex pattern
- Subdomains & DNS related data

The extracted information is saved in an organized manner or can be [exported as json](https://github.com/s0md3v/Photon/wiki/Usage#export-formatted-result).

![save demo](https://image.ibb.co/dS1BqK/carbon_2.png)

#### Flexible
Control timeout, delay, add seeds, exclude URLs matching a regex pattern and other cool stuff.
The extensive range of [options](https://github.com/s0md3v/Photon/wiki/Usage) provided by Photon lets you crawl the web exactly the way you want.

#### Genius
Photon's smart thread management & refined logic gives you top notch performance.

Still, crawling can be resource intensive but Photon has some tricks up it's sleeves. You can fetch URLs archived by [archive.org](https://archive.org/) to be used as seeds by using `--wayback` option.

#### Plugins
- **[wayback](https://github.com/s0md3v/Photon/wiki/Usage#use-urls-from-archiveorg-as-seeds)**
- **[dnsdumpster](https://github.com/s0md3v/Photon/wiki/Usage#dumping-dns-data)**
- **[Exporter](https://github.com/s0md3v/Photon/wiki/Usage#export-formatted-result)**

#### Docker

Photon can be launched using a lightweight Python-Alpine (103 MB) Docker image.

```bash
$ git clone https://github.com/s0md3v/Photon.git
$ cd Photon
$ docker build -t photon .
$ docker run -it --name photon photon:latest -u google.com
```

To view results, you can either head over to the local docker volume, which you can find by running `docker inspect photon` or by mounting the target loot folder:

```bash
$ docker run -it --name photon -v "$PWD:/Photon/google.com" photon:latest -u google.com
```

#### Frequent & Seamless Updates
Photon is under heavy development and updates for fixing bugs. optimizing performance & new features are being rolled regularly.

If you would like to see features and issues that are being worked on, you can do that on [Development](https://github.com/s0md3v/Photon/projects/1) project board.

Updates can be installed & checked for with the `--update` option. Photon has seamless update capabilities which means you can update Photon without losing any of your saved data.

### Contribution & License
You can contribute in following ways:

- Report bugs
- Develop plugins
- Add more "APIs" for ninja mode
- Give suggestions to make it better
- Fix issues & submit a pull request

Please read the [guidelines](https://github.com/s0md3v/Photon/wiki/Guidelines) before submitting a pull request or issue.

Do you want to have a conversation in private? Hit me up on my [twitter](https://twitter.com/s0md3v/), inbox is open :)

**Photon** is licensed under [GPL v3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

⚠️ Read-First:

🔞The author of the does not encourage anyone to repeat this. Otherwise, you will be solely responsible. The was created for informational purposes. And for the fact that you caution you!🙏

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

Description 👀

Title 📌 Photon

💀 Made by ☠️👊 𝕿𝖍𝖎𝖘 𝕴𝖘 𝕿𝖍𝖊 𝓜4𝓷𝓲𝓯𝓮𝓼𝓽0 𝕿𝖊𝖆𝖒™💪🏴‍☠️

Author 🏴‍☠️ rainboy1 | erfan4lx | Vampire4lx

Aate ♾ 2020 May

Version 👁‍🗨 2.0.0

Usage 👌 cd Photon

Channel  Combo List 👍  [![Telegram Chanel](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lxCombo)


✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

☠️👊𝓷𝓲𝓯𝓮𝓼𝓽4𝓷𝓲𝓯𝓮𝓼𝓽0 (MCS) Telegram Groups We are a team of  𝓑𝓵𝓪𝓬𝓴  𝓗𝓪𝓽  𝓗𝓪𝓬𝓴𝓮𝓻𝓼  because we know what is at stake. We prepare hackers by providing training and hacking tools. We are one of the few Black hat hacking teams that show you their skills.👁‍🗨💪

👇🏾👇🏾👇🏾👇🏾👇🏾

[![Join To Telegram Groups](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/M4nifest0)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

Telegram Chat ID 📞 [![Telegram Chat](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lx)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

<p align="center">
  ✯ Follow Me On ♥️👇🏾👇🏾👇🏾
</p>
<p align="center">
  <a href="https://www.youtube.com/channel/UC73xXDVwfS8mE4ExtOg63sw/videos?view_as=subscriber">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIe0KA-4U2wilfj3CwcetOZYjaXr_C6bh5b9Xp3eDfeATwkhn82b70ELBt&s" width="40" height="40">
  </a>
  <a href="https://t.me/M4nifest0">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnOo5m2bMLsKVd9-ZjGf0xl0SAVqj9Fgxvu89_iu24qUcWQJ-X_1lvI5yOIA&s" width="40" height="40">
</p>

