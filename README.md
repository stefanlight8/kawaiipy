kawaiipy – async wrapper for [Kawaii API](https://kawaii.red/).

### Install
```py
pip install kawaiipy
```

### Use example
```py
import kawaiipy

api: KawaiiAPI = KawaiiAPI()


async def main() -> None:
    """Get image of hugs!"""
    image: str = await api.get("gif", "hug")
    print(image)


if __name__ == "__main__":
    asyncio.run(main)
```

### Recommendation
Use the -O and -OO flags to ignore docstrings and assertions while interpretation process.
