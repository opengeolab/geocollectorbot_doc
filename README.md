# Geo Collector Bot documentation

Documentation for users and developers of Telegram Bot [Geo Collector Bot](https://geocollectorbot-doc.readthedocs.io).

## Local development

The documentation is built using [Sphinx](https://www.sphinx-doc.org/en/master/index.html), therefore it requires
Python to run.

1. Install [Python 3](https://www.python.org/) and check the installation
  ```shell
  python3 -V
  ```
2. Create a new virtual environment and activate it
  ```shell
  python3 -m venv .venv
  source .venv/bin/activate
  ```
3. Install the required packages
  ```shell
  pip3 install -r requirements.txt
  ```
4. Build the docs
  ```shell
  sphinx-build -b html docs/source/ docs/build/html
  ```
5. Serve the docs on [localhost:8000](http://localhost:8000/)
  ```shell
  cd docs/build/html && python3 -m http.server
  ```
