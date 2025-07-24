# handbook

simple boilerplate for the handbook

## Usage

### Building the book

If you'd like to develop and/or build the handbook book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `handbook/` directory
4. Run `jupyter-book clean handbook/` to remove any existing builds
5. Run `jupyter-book build handbook/`

A fully-rendered HTML version of the book will be built in `handbook/_build/html/`.

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` for the `include_ci` cookiecutter option, your book template was created with a GitHub actions workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/WHO-Collaboratory/collaboratory-handbook/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).

## Returning Contributors

#### 1. Go to where the repo is stored on your local computer:  

Example:  
```bash
▶ pwd                                                                                      
/Users/reshamas/rs_repos/collaboratory-handbook
(base)
```

2. Reminder: create a new branch for pull requests in lieu of submitting pull requests to the `main` branch:  
Example:  
```bash
~/rs_repos/collaboratory-handbook  main ✔                                                   3d1h  
▶ git checkout -b rs-cm-faqs                                                                
Switched to a new branch 'rs-cm-faqs'
(base) 
~/rs_repos/collaboratory-handbook  rs-cm-faqs ✔ 
```

3.  Reminder: ensure you are in the correct directory to build and test your jupyterbook.
Example:  
```bash
▶ cd handbook                                                                             
(base) 
rs_repos/collaboratory-handbook  rs-cm-faqs ✗                                    3d1h ⚑  
▶ pwd                                                                                     
/Users/reshamas/rs_repos/collaboratory-handbook
(base) 
rs_repos/collaboratory-handbook  rs-cm-faqs ✗                                    3d1h ⚑  
▶             
```

4. [Build your jupyterbook locally](https://jupyterbook.org/en/stable/start/build.html#aside-source-vs-build-files)

```bash
jupyter-book build --all mybookname/
```
or
```bash
jupyter-book build mybookname/
```

5. Go to the browser and see the build. The link will be provided in your terminal

Example:  
[my local browser link](file:///Users/reshamas/rs_repos/collaboratory-handbook/handbook/_build/html/index.html)            


