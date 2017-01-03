siggraph2016_colorization
=====
[Torch7](http://torch.ch/) + [siggraph2016_colorization](http://hi.cs.waseda.ac.jp/~iizuka/projects/colorization/en/).

Torch7 is pulled from [kaixhin/torch](https://hub.docker.com/r/kaixhin/torch/).

Usage
-----
Run sample code `docker run -t [tag_name] th colorize.lua ansel_colorado_1941.png out.png`

Copy output file to local `docker cp [container_id]:/root/siggraph2016_colorization/out.png ./out.png`

For details, [satoshiiizuka/siggraph2016_colorization](https://github.com/satoshiiizuka/siggraph2016_colorization).