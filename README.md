# zanph

##first things first:

OSX:

* install xcode command-line tools

`xcode-select --install`

* install homebrew:

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

* install zmq:

`brew install zmq`

* install python with homebrew (also installs Setuptools and pip)

`brew install python`

* install python zmq bindings

`easy_install pyzmq`
or
`pip install --wheel pyzmq`
or
`pip install pyzmq`


###using the flask site with virtual env:

* install virtual env
 
`pip install virtualenv`

there is a virtual env folder `venv` in `/flaskroulette` with all necessary packages installed. to use it, do

`. venv/bin/activate` from `/flaskroulette`.



###other stuff we might use at some point maybe
* postgreSQL:

`brew install postgreSQL`

* scrapy:

`pip install scrapy`

* requests:

`pip install requests`

* flask:

`pip install flask`
