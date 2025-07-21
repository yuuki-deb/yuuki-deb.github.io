## AviSynth+ and x265 Yuuki Debian Repository

For trixie:

```
wget -O /etc/apt/sources.list.d/yuuki-deb.sources https://yuuki-deb.x86.men/yuuki-deb.sources
wget -O /usr/share/keyrings/yuuki-deb.gpg https://yuuki-deb.x86.men/yuuki-deb.gpg
```

For old Debian releases:

```
curl https://yuuki-deb.x86.men/yuuki-deb.gpg | apt-key add -
echo "deb http://yuuki-deb.x86.men/ $(lsb_release -sc) main" > /etc/apt/sources.list.d/yuuki-deb.list
```
