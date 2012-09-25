# Getting Started with Flask and Templates

Templates keep your code separated from your code and vice versa. Using templates allows you to focus on the code, logic and data then pass the needed data to an HTML template.

People often call this MVC, of Model-View-Controller, where data structures (M), templates (V) and code (C) are separated into different files and directories.

## Templates

Our templates are located in the /templates directory. These can be organized in directories if needed. The templates are regular HTML files

## Quick Start

* Download code.
* Open code directory in Terminal console.
* Create Virtualenv (only needs to be run once).

		virtualenv venv

* Initial PIP requirements install / Or when you need to update Python modules after modifying requirements.txt

		. runpip

	The **runpip** file is a helper file and has the following commands

		. venv/bin/activate
		pip install -r requirements.txt

* Start the Server & Activate the Virtualenv if not already active.

		. start

	The **start** file has the following commands

		. venv/bin/activate
		foreman start

* If successful you can navigate to <a href="http://localhost:5000">http://localhost:5000</a>.
