# When I try to create virtual environment, I met the following error.  How can I fix it? 
PS C:\Users\windr\Documents\GitHub\django-girl> python -m venv myvenv
Error: [Errno 2] No such file or directory: 'C:\\Program
Files\\Python37\\lib\\venv\\scripts\\nt\\python_d.exe'

Answer: This is due to the python 3.7.3 windows version from the link below.
https://stackoverflow.com/questions/55380296/how-to-fix-error-errno-2-no-such-file-or-directory-c-program-files-pytho
We just need to install a different version of python. After install python
3.8.1 the problem is resolved.
