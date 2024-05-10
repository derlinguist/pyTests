# Notes
## Codepilot Prompts

### Click, Dyn Modules, Setuptools
I need the a template structure for a python app using setuptools with pyprojects.toml to deploy the app. the python app shall use the Click package to implement a CLI. The app also consists of a main module multiple sub-modules (e.g. use A, B, C, ... to name them in the template) which are not fixed. Hence the sub-modules must be loaded dynamically into the python path by the app. each of these sub-modules realizes a sub-command for the Click based CLI. Confirm that you have understood the initial situation.
