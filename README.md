<h1 align="center">IRSIM-PY</h1>

> 编译原理的 lab3 竟然只提供`.pyc`的程序供执行和调试中间代码。由于`.pyc`的固有缺陷，这个程序只能在 Linux 平台 Python3.8 环境运行，这显然不可接受。好在有成熟的 pyc 文件反编译方案，经过一番查找后，我选择使用[PyLingual](https://pylingual.io)进行反编译。反编译相对顺利，经过我的一些小修改，项目成功运行起来，看似一切正常。

## Quick Start

```shell
uv sync
uv run irsim.py
```

## TODO

- [ ] 命令行版本
- [ ] 构建 CI 流水线，打包多平台单可执行文件
