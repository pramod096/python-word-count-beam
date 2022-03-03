# python-word-count-beam
### Pramod Reddy Gonegari

##### Steps to set up your Python development environment, get the Apache Beam SDK for Python, and run an example pipeline.


1. Create a new folder named python-word-count-beam and open powershell as administrator at this directory.

2. Add wordcount.py and input.txt from quick start [examples.](https://github.com/apache/beam/tree/master/sdks/python/apache_beam/examples)

3. Install [pip](https://pip.pypa.io/en/stable/installing/).
```
pip --version
```

4. Upgrade to latest pip version.
```
python -m pip install --upgrade pip
```

5. Create and activate a virtual environment
```
python -m venv C:\path\to\directory

C:\path\to\directory\Scripts\activate.ps1
```

6. Download and install Apache Beam.
```
python -m pip install apache-beam
```

7. Execute the wordcount.py
```
python -m apache_beam.examples.wordcount --input /path/to/inputfile --output /path/to/write/counts
```

### Output
![Output Image](https://raw.githubusercontent.com/pramod096/python-word-count-beam/main/images/output.png)




