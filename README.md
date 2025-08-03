```
apt-get update && apt-get install tmux -y && curl -LsSf https://astral.sh/uv/install.sh | sh && source $HOME/.local/bin/env
uv tool run copyparty -p 8000 -a user:pokemon -v .::A,user --allow-csrf --xff-hdr cf-connecting-ip
```
