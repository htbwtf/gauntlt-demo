TEST vuln-08.attack

This is a Gauntlt test to check if the vulnerability in WebGoat located at Cross-Site Scripting (XSS) => Reflected XSS Attacks (vuln-08) exists.

It will fail if the vulnerability is present,
or pass if the vulnerablity is fixed (AKA not present).

The test assumes that:

1) The Python script is in /home/hacker/gauntlt-demo/examples/webgoat/vuln-08, and the full path is listed in the .attack file (line 5).

2) The requests Python package is installed. To do this, we went to 
https://pypi.python.org/pypi/requests#downloads
Downloaded the tar.gz file, uncompress, and run:
python setup.py install
in the uncompressed directory in the ROOT terminal.
