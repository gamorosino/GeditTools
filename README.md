# GeditTools
Useful gedit external tools

## How to use

### Gedit Plug-ins

Check if gedit-plugins is installed.If not, install them as follows:

1. Enable "Universe" repository
2. Install gedit-plugins
3. Activate "Embedded Terminal"
4. Copy the tools files in the config folder

#### 1. Enable "Universe" repository

sudo add-apt-repository universe
sudo apt-get update

#### 2.Install gedit-plugins

Install gedit-plugs with the command:

sudo apt install gedit-plugins

#### 3. Activate "Embedded Terminal" *

Open gedit and then select Edit->Preferences->Plugins and check off Embedded Terminal

* n.b. Compulsory activated for "Run Script" and "Execute Current Line" tools

### 4. Copy Files

Copy the contents of the "tools" folder into the directory of the gedit tools configuration folder which is generally "~/.config/gedit/tools" (if not, create it)

#### Run Script

Once gedit is open, it is possible to use the short-cuts (F5) or open from the drop-down menu Tools-> Extranl Tools-> Run Script

This command run the current document (script) in the Embedded Terminal. The script could be ".sh" (run with bash env) or ".py" (run with python env) or ".m" (run with matlab)

#### Run Script External

Once gedit is open, it is possible to use the short-cuts (ctrl+F5) or open from the drop-down menu Tools-> Extranl Tools-> Run Script External

This command run the current document (script) in an external gnome-terminal (bash env). The script could be ".sh" (run with bash env) or ".py" (run with python env) or ".m" (run with matlab)

#### Execute Current Line

Once gedit is open, it is possible to use the short-cuts (ctrl+E) or open from the drop-down menu Tools-> Extranl Tools-> Execute Current Line

This command run the current line selected in the document (script) in the Embedded Terminal. The script could be ".sh" (run with bash env) or ".py" (run with python env).

