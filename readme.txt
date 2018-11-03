python -m pydoc

# keyword search
python -m pydoc -k ftp

# module doc
python -m pydoc ftplib

# module doc
python
>>>import ftplib
>>>help(ftplib)

# pydoc server at port
python -m pydoc -p 8080

# pydoc server at random available port
python -m pydoc -b

# pydoc file
>>> mkdir pydoc_demo
>>> cd pydoc_demo
>>> python -m pydoc -w json