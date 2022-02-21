Microsoft Windows [Versión 10.0.19043.1526]
(c) Microsoft Corporation. Todos los derechos reservados.

C:\Users\Pc\Documents\Python Scripts>pip install virtualenv
Collecting virtualenv
  Downloading virtualenv-20.13.1-py2.py3-none-any.whl (8.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.6/8.6 MB 6.9 MB/s eta 0:00:00
Requirement already satisfied: platformdirs<3,>=2 in c:\users\pc\appdata\roaming\python\python39\site-packages (from virtualenv) (2.5.0)
Collecting filelock<4,>=3.2
  Downloading filelock-3.5.1-py3-none-any.whl (10.0 kB)
Requirement already satisfied: six<2,>=1.9.0 in c:\users\pc\appdata\roaming\python\python39\site-packages (from virtualenv) (1.16.0)
Collecting distlib<1,>=0.3.1
  Downloading distlib-0.3.4-py2.py3-none-any.whl (461 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 461.2/461.2 KB 7.2 MB/s eta 0:00:00
Installing collected packages: distlib, filelock, virtualenv
Successfully installed distlib-0.3.4 filelock-3.5.1 virtualenv-20.13.1

C:\Users\Pc\Documents\Python Scripts>python -m venv env

C:\Users\Pc\Documents\Python Scripts>env¨*[Ñ
"env¨*[Ñ" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\Users\Pc\Documents\Python Scripts>env\scripts\activate

(env) C:\Users\Pc\Documents\Python Scripts>pip freeze

(env) C:\Users\Pc\Documents\Python Scripts>pip install python-dateutil
Collecting python-dateutil
  Using cached python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
Collecting six>=1.5
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Installing collected packages: six, python-dateutil
Successfully installed python-dateutil-2.8.2 six-1.16.0
WARNING: You are using pip version 20.2.3; however, version 22.0.3 is available.
You should consider upgrading via the 'c:\users\pc\documents\python scripts\env\scripts\python.exe -m pip install --upgrade pip' command.

(env) C:\Users\Pc\Documents\Python Scripts>pip freeze
python-dateutil==2.8.2
six==1.16.0

(env) C:\Users\Pc\Documents\Python Scripts>deactivate
C:\Users\Pc\Documents\Python Scripts>