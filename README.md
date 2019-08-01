### uvloop
---
https://github.com/MagicStack/uvloop

```py
import asyncio
import uvloop

async def main():
uvloop.install()
asyncio.run(main())

```

```sh
pip install uvloop
git clone --recursive git@github.com:MagicStack/uvloop.git
cd uvloop
python3.7 -m venv uvloop-dev
source uvloop-dev/bin/activate
pip install -r requirements.dev.txt
make
make test
```

```
```


