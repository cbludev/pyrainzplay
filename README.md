# pyrainzplay

create a tag from 'branch' - namely, RELEASE_0.0.1
update the tag version in property file
simulation=v_0.0.2
processing=v_0.0.1
- click refresh and update all servers to download scripts from new lib version from some url like:

python3.4 onwards pip automically bootstrapped
	- In win, use py -m pip show <module_name>

pip --version
pip uninstall

upload code in git
create release/tag branch: https://github.com/cbludev/pyrainzplay/archive/0.0.1.zip
upload to pypi repo, run following from code folder: (upon release click button, via script in generate zipped packages and upload in repo!)
	py setup.py sdist --formats=gztar,zip
	pip install twine
	// requires credentials
	py -m twine upload dist/*

// local install on machine
pip install --target=<custom_path> -U
py -m pip show pyrainzplay
