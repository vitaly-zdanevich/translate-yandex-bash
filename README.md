# translate-yandex-bash
Simple script for en-ru/ru-en translation

Linux: put `trans` to `/usr/bin/`, Mac `/usr/local/bin/`:  make executable by `sudo chmod +x trans`, restart terminal and now you can:

`trans hello`

`trans привет`

`trans good morning`

`trans доброе утро`

Also it usefull not to switch layout when typing:

`транс привет`

For this you can create soft link at the same folder:

`ln -s trans транс`
