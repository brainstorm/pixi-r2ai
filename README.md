# Quickstart

```shell
$ brew install pixi --HEAD
$ pixi install
$ pixi run install_r2ai
$ pixi shell
```

# Intro

There should be an easier way to install radare2's AI than the official way:

```
The easiest way to run and install r2ai is by installing the latest r2 from git and run these lines:
pip3 install rich inquirer llama-cpp tokentrim hugging_face appdirs
pip install rich inquirer llama-cpp-python tokentrim hugging_face appdirs
On native Windows follow these instructions (no need to install radare2 or use r2pm), note that you need Python 3.8 or higher:
python -m pip install rich inquirer llama-cpp-python tokentrim hugging_face appdirs pyreadline3
It's also possible to install it with `conda`, which is the recommended way on Macs.
conda install pytorch torchvision torchaudio -c pytorch-nightly
conda run pip install inquirer rich appdirs huggingface_hub tokentrim llama-cpp-python
ln -fs /Users/rvalls/.local/share/radare2/r2pm/git/r2ai/main.py /Users/rvalls/.local/share/radare2/plugins/r2ai.py
ln -fs /Users/rvalls/.local/share/radare2/r2pm/git/r2ai/main.py /Users/rvalls/.local/share/radare2/prefix/bin/r2ai
```

This repo explores this while giving [Pixi](prefix_dev) a try!

[prefix_dev]: https://prefix.dev/
