# Interview.Codes Classes

On my site [Interview.Codes](https://interview.codes/), I offer several courses for interview preparation. As part of the course I provide sample implementations to the algorithsm discussed. That code is stored here.

You can take all of my courses on [SkillShare profile](https://www.skillshare.com/r/profile/Edaqa-Mortoray/8551496).


# Python Virtual Environment

## Linux / Mac

Be sure to use `python3` on Linux, as multiple versions may be installed.

```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## Windows - Command Prompt

```
python -m venv env
env\Scripts\activate.bat
pip install -r requirements.txt
```

## Windows - Power Shell

By default the virtual environment scripts will be blocked from running. This will disable that check. _If somebody knows of a more fine-grained permission change, let me know and I'll update this reference._

As Administrator:
```
Set-ExecutionPolicy Unrestricted
```

As user:
```
python -m venv env
env\Scripts\activate.ps1
pip install -r requirements.txt
```
