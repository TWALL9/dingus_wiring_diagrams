# dingus_wiring_diagrams
Basic wiring diagrams for the otomo/dingus robot

# How to use
The yaml files in this repo are for [WireViz](https://github.com/wireviz/WireViz/tree/master). To run WireViz

1. Create a python virtual environment

```bash
python3 -m venv /path/to/somewhere
. /path/to/somewhere/bin/activate
```

2. Install WireViz
```bash
pip3 install -r requirements.txt
# OR
pip3 install wireviz
```

3. Run WireViz
```bash
wireviz /path/to/dingus_wiring_diagrams/*.yaml
```

4. Marvel at how convoluted the wiring is
