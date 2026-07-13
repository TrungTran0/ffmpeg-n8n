`docker exec -u 0 -it id /bin/sh`

`wget https://tool.trungtran.site/ffmpeg/apk.static`

`chmod +x apk.static`

`./apk.static -X https://tool.trungtran.site/alpine/v3.24/community -U --allow-untrusted --initdb add apk-tools`

`apk add ffmpeg --repository=https://tool.trungtran.site/alpine/v3.24/community --allow-untrusted`

if error:
/home/node # ./apk.static -X https://tool.trungtran.site/alpine/v3.24/community -U --allow-untrusted --initdb add apk-tools

fetch https://tool.trungtran.site/alpine/v3.24/community/x86_64/APKINDEX.tar.gz

fetch https://dl-cdn.alpinelinux.org/alpine/v3.22/main/x86_64/APKINDEX.tar.gz

fetch https://dl-cdn.alpinelinux.org/alpine/v3.22/community/x86_64/APKINDEX.tar.gz

ERROR: unable to select packages:
  libapk2-2.14.10-r0:
    breaks: world[libapk2><Q1kC/XFkbW4IfkcsZ7D2NMBDohlbw=]
    satisfies: apk-tools-2.14.10-r0[so:libapk.so.2.14.10]

then run:

`rm -rf /lib/apk`

`rm -rf /var/lib/apk`

`rm -f /etc/apk/world`

`./apk.static -X https://tool.trungtran.site/alpine/v3.24/community -U --allow-untrusted --initdb add apk-tools`

`apk add ffmpeg --repository=https://tool.trungtran.site/alpine/v3.24/community --allow-untrusted`
