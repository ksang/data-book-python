# data-book-python
Python code for the book: Data Driven Science &amp; Engineering, authors:  Steven L. Brunton, J. Nathan Kutz

Book Website: http://databookuw.com

Book PDF: http://databookuw.com/databook.pdf

### prepare environment

- [direnv](https://direnv.net/), can be skipped by running commands in [.envrc](.envrc) manually.

- [pyenv](https://github.com/pyenv/pyenv) with [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) plugin. To install python 3.9.9 and create a virtual env based on it:
    ```
    pyenv install 3.9.9
    pyenv virtualenv 3.9.9 `basename "$PWD"`
    ```

- Install dependencies
    ```
    pip install -r requirements.txt
    ```