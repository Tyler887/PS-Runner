# PowerShell VM Environment
GitHub Action to execute Windows Power shell commands on GitHub.

To run, go to the Actions tab, see "PowerShell virtual environment", click `Run workflow`, and set the server to run Windows on (`2019` or `latest`), as well as the command to run and the [actions/checkout](https://github.com/marketplace/actions/checkout) version..

GitHub then connects to your specified server to run Windows PowerShell and run your command.

By default, the following is set for the workflow run:
* Command: `echo "Hello World"`
* Server: Latest version (`latest`)
* Checkout version: `v2` (Latest version.)
