
#  A Beginners Guide to MkDocs

*Project documentation with markdown*


<p>MkDocs is a quick and easy way to create static HTML sites for project documentation.  The documentation source files are written in Markdown and configured with a single YAML file.

Markdown is a lightweight markup language that can be used to format textual documents. while
YAML is a human-readable data serialization language that is used to create configuration files in which data is sent or saved. </p>


## Why MkDocs

There are a lot of themes available for MkDocs. You can choose from its built-in themes (mkdocs and readthedocs), import a third-party theme (on the MkDocs Themes wiki page as well as Best-of-MkDocs), or build your own.

MkDocs lets you personalize your project documentation by tweaking your theme and/or installing plugins. Add more extensions and configuration options to modify markdown behavior.

Preview your documentation as you work using the built-in deb server and also auto-reload and refresh your browser when you save changes.

Your websites can be hosted on Github Pages, Amazon, or anywhere else you like.


## How it Works
Mkdocs requires  a recent version of Python and the Python package manager, pip installed on your system.

To see if you have Python and Pip installed, Run the following commands from the command line:




Skip ahead to installation if you already have these program installed


## Installing MkDocs

MkDocs is installed using Python Package Manager ,Pip. Run this  command to install MkDocs:

    Pip install MkDocs

The MkDocs is now installed on your device. Check if everything worked okay by running:

        MkDocs version


## Creating a New project.

 To create a new project, run the following:

    Mkdocs new  my-project
    cd my project

Your new project should contain a single configuration file **(mkdocs .yml)** and a folder, **doc** that will contain your documentation source file

Because Mkdocs includes a built-in dev server that gives preview while you work, you may start it by running the mkdocs serve command:

    mkdocs serve `
    INFO     -  Building documentation...
    INFO     -  Cleaning site directory
    INFO     -  Documentation built in 0.22 seconds
    INFO     -  Documentation built in 0.22 seconds
    INFO     -  [12:35:34] Watching paths for changes: 'docs', 'mkdocs.yml'
    INFO     -  [12:35:34] Serving on http://127.0.0.1:8000/


In your browser, navigate to http://127.0.0.1:8000/ to see the default home page:


![home](https://www.mkdocs.org/img/screenshot.png)




 - ## Installing Python and PIP
Python can be installed using a package manager of yoyur choice or by downloading an appropriate installer from 
   [python.org](https://www.python.org)


 - ### Intalling PIP
Python Package manager, PIP is  usually installed by default in recent versions of Python.However it might need an upgrade:

        pip install --upgrade pip
 

## Adding Pages

To add a new page to your documentation:

1.Create a new file from your test editor or command line

2.Add information about the order, title, and nesting of each page in the navigation header to the configuration file by adding a nav setting


## Theming Documentation


To change how documentation is shown, add a theme setting by editing the comfiguration file,the mkdocs.yml file.



    theme:
        name: readthedocs

Save your adjustments to see your theme in action.

## Building and Deploying

Your documnention site should be built before deploying . Here is how to build your site:

    mkdocs build
<p>
The newly constructed documentation site uses only static files, allowing you to host it nearly anywhere by simply uploading the contents of the complete site directory to wherever you host your website, and you're done.</p>


## Help and Additional Resources
* For full doumentation visit [Mkdocs.org](https://www.mkdocs.org/).
* Use [GitHub Discussions](https://github.com/mkdocs/mkdocs/discussions) [GitHub issues](https://github.com/mkdocs/mkdocs/issues) for more help with MkDocs.


