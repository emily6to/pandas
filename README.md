# Pandas

###  Mostrar ultimas 10 filas del dataframe

~~~~

print(df.tail(10))

~~~~

Resultado:

~~~~

PS C:\Users\Pc5> & C:/Users/Pc5/AppData/Local/Programs/Python/Python312/python.exe c:/Users/Pc5/pandas
Traceback (most recent call last):
  File "c:\Users\Pc5\pandas", line 3, in <module>
    df = pd.read_csv('historico-nombres.csv')
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1026, in read_csv
    return _read(filepath_or_buffer, kwds)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 620, in _read    
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1620, in __init__
    self._engine = self._make_engine(f, self.engine)
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1880, in _make_engine
    self.handles = get_handle(
                   ^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\common.py", line 873, in get_handle
    handle = open(
             ^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'historico-nombres.csv'
PS C:\Users\Pc5> & C:/Users/Pc5/AppData/Local/Programs/Python/Python312/python.exe c:/Users/Pc5/pandas
Traceback (most recent call last):
  File "c:\Users\Pc5\pandas", line 3, in <module>
    df = pd.read_csv('historico-nombres.csv')
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1026, in read_csv
    return _read(filepath_or_buffer, kwds)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 620, in _read
    parser = TextFileReader(filepath_or_buffer, **kwds)
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1620, in __init__
    self._engine = self._make_engine(f, self.engine)
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1880, in _make_engine
    self.handles = get_handle(
                   ^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\common.py", line 873, in get_handle
    handle = open(
             ^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'historico-nombres.csv'
PS C:\Users\Pc5>

~~~~

### Mostrar informacion del dataframe

~~~~

print(df.info())

~~~~

Resultado:

~~~~

PS C:\Users\Pc5> & C:/Users/Pc5/AppData/Local/Programs/Python/Python312/python.exe c:/Users/Pc5/pandas
Traceback (most recent call last):
  File "c:\Users\Pc5\pandas", line 3, in <module>
    df = pd.read_csv('historico-nombres.csv')
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1026, in read_csv
    return _read(filepath_or_buffer, kwds)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 620, in _read    
    parser = TextFileReader(filepath_or_buffer, **kwds)
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1620, in __init__
    self._engine = self._make_engine(f, self.engine)
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1880, in _make_engine
    self.handles = get_handle(
                   ^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\common.py", line 873, in get_handle
    handle = open(
             ^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'historico-nombres.csv'
PS C:\Users\Pc5>

~~~~

### Obtener valores estadisticos del dataframe

~~~~

print(df.describe())

~~~~

Resultado:

~~~~

PS C:\Users\Pc5> & C:/Users/Pc5/AppData/Local/Programs/Python/Python312/python.exe c:/Users/Pc5/pandas
Traceback (most recent call last):
  File "c:\Users\Pc5\pandas", line 3, in <module>
    df = pd.read_csv('historico-nombres.csv')
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1026, in read_csv
    return _read(filepath_or_buffer, kwds)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 620, in _read    
    parser = TextFileReader(filepath_or_buffer, **kwds)
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1620, in __init__
    self._engine = self._make_engine(f, self.engine)
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1880, in _make_engine
    self.handles = get_handle(
                   ^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\common.py", line 873, in get_handle
    handle = open(
             ^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'historico-nombres.csv'
PS C:\Users\Pc5>

~~~~

### Obtener el tamaño del dataframe

~~~~

print(df.shape)

~~~~

Resultado:

~~~~

PS C:\Users\Pc5> & C:/Users/Pc5/AppData/Local/Programs/Python/Python312/python.exe c:/Users/Pc5/pandas
Traceback (most recent call last):
  File "c:\Users\Pc5\pandas", line 3, in <module>
    df = pd.read_csv('historico-nombres.csv')
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1026, in read_csv
    return _read(filepath_or_buffer, kwds)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 620, in _read    
    parser = TextFileReader(filepath_or_buffer, **kwds)
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1620, in __init__
    self._engine = self._make_engine(f, self.engine)
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1880, in _make_engine
    self.handles = get_handle(
                   ^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\common.py", line 873, in get_handle
    handle = open(
             ^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'historico-nombres.csv'
PS C:\Users\Pc5>

~~~~

### Seleccionar una columna con [] (forma preferida de seleccionar una columna)

~~~~

print(df['nombre'])

~~~~

Resultado:

~~~~

PS C:\Users\Pc5> & C:/Users/Pc5/AppData/Local/Programs/Python/Python312/python.exe c:/Users/Pc5/pandas
Traceback (most recent call last):
  File "c:\Users\Pc5\pandas", line 3, in <module>
    df = pd.read_csv('historico-nombres.csv')
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1026, in read_csv
    return _read(filepath_or_buffer, kwds)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 620, in _read    
    parser = TextFileReader(filepath_or_buffer, **kwds)
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1620, in __init__
    self._engine = self._make_engine(f, self.engine)
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1880, in _make_engine
    self.handles = get_handle(
                   ^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\common.py", line 873, in get_handle
    handle = open(
             ^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'historico-nombres.csv'
PS C:\Users\Pc5>

~~~~

### Seleccionar 2 columnas usando [[]]

~~~~

print(df[['nombre', 'edad']])

~~~~

Resultado:

~~~~

PS C:\Users\Pc5> & C:/Users/Pc5/AppData/Local/Programs/Python/Python312/python.exe c:/Users/Pc5/pandas
Traceback (most recent call last):
  File "c:\Users\Pc5\pandas", line 3, in <module>
    df = pd.read_csv('historico-nombres.csv')
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1026, in read_csv
    return _read(filepath_or_buffer, kwds)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 620, in _read    
    parser = TextFileReader(filepath_or_buffer, **kwds)
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1620, in __init__
    self._engine = self._make_engine(f, self.engine)
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\parsers\readers.py", line 1880, in _make_engine
    self.handles = get_handle(
                   ^^^^^^^^^^^
  File "C:\Users\Pc5\AppData\Local\Programs\Python\Python312\Lib\site-packages\pandas\io\common.py", line 873, in get_handle
    handle = open(
             ^^^^^
FileNotFoundError: [Errno 2] No such file or directory: 'historico-nombres.csv'
PS C:\Users\Pc5>

~~~~

