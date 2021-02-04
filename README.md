# Snippets & Issues

## ipykernel not installed into interpreter VSCode

```shell
pip install pyzmq --force-reinstall
pip install jupiter-client --force-reinstall
```

## Default asyncio event loop on windows python >= 3.8

```python
if sys.platform == 'win32':
    asyncio.set_event_loop_policy(asyncio.WindowsSelectorEventLoopPolicy())
```
