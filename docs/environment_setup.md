# How to set up the environment

1. Clone the repo or unzip the directory, say to D:\My Documents\AltoMultiModalCorridor\AltoMultiModalCorridor

2. Cd to the top level: cd D:\My Documents\AltoMultiModalCorridor\AltoMultiModalCorridor

3. Install Ruby from https://rubyinstaller.org/downloads/. Choose the 3.1.7 version of the Ruby+Devkit install (you may need to look in the archives for this)

4. install Ruby+Devkit from RubyInstaller. choose MSYS2 and MINGW development toolchain when prompted.

5. Completely close *all* VSCode windows. You need to do this otherwise the powershell windows inside VSCode will not see the environmnet variables from the new Ruby install.

6. Open VSCode to the top level directory. Open a powershell terminal.

7. In VSCode, in the powershell terminal type:
```
ruby -v
gem -v
```
These command should work. They show that ruby and gem are installed. You want ruby -v to show 3.1.7.

If they work type:
```
gem install bundler
bundle -v
bundle install
bundle exec jekyll serve
```
Now, you should be up and running. 

Open a browser window to:
```
http://127.0.0.1:4000/
```