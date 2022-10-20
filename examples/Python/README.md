
# WebUI Examples - Python

To use WebUI in your Python script, you will need to [build](https://github.com/alifcommunity/webui/tree/main/build) the WebUI library first using your favorite C compiler, then copy into this folder the dynamic WebUI library, `webui-2-x64.dll` on Windows, or `webui-2-x64.so` on Linux. Or, instead of coping the lib you can specify the path in your python script `webui.set_library_path("path/to/webui")`

```sh
python main.py
```