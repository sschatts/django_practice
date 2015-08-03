Virtual Environment Set-up Steps:

1. Install pip: sudo python get-pip.py
[sudo for mac to install globally]
2. pip freeze > requirements.txt
[to see installed Python packages]
3. Install vitualenv: sudo pip install virtualenv
4. Install virtualenvwrapper: sudo pip install virtualenvwrapper
5. Update the bash_profile: ls -la ~/.
   Find .bash_profile
   Edit it by: vim ~/.bash_profile, press 'i' in the terminal to insert
       # virtualenv
        export WORKON_HOME=$HOME/.virtualenvs
        export PROJECT_HOME=$HOME/Repos/git/
        source /usr/local/bin/virtualenvwrapper.sh

        alias venv="workon"
        alias venv.exit="deactivate"
        alias venv.ls="lsvirtualenv"
        alias venv.show="showvirtualenv"
        alias venv.init="mkvirtualenv"
        alias venv.rm="rmvirtualenv"
        alias venv.switch="workon"
        alias venv.add="add2virtualenv"
        alias venv.cd="cdproject"
        alias venv.cdsp="cdsitepackages"
        alias venv.cdenv="cdvirtualenv"
        alias venv.lssp="lssitepackages"
        alias venv.proj="mkproject"
        alias venv.setproj="setvirtualenvproject"
        alias venv.wipe="wipeenv"
  Then :wq to save it
  Have to source the same file for the computer to recognize the edits: source ~/.bash_profile
6. Make virtual environment: mkvirtualenv name
7. Additional set to install django for the first time:
   pip install django==1.7
   //1.7 should be the version number you want to download

From here went on to follow the tango with django tutorial: http://www.tangowithdjango.com/book17/chapters/setup.html

Follow along at tang0_with_django_tutorial.md
