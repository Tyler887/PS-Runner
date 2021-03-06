# PowerShell VM Environment
GitHub Action to execute Windows Power shell commands on GitHub.

To run, go to the Actions tab, see "PowerShell virtual environment", click `Run workflow`, and set the [server](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners#supported-runners-and-hardware-resources) to run Windows on (`2022`, `2019` or `latest`), as well as the command to run.

GitHub then connects to your specified server to run Windows PowerShell and run your command.

By default, the following is set for the workflow run:
* Command: `echo "Hello World"`
* Server: Latest version (`2022`)<br>`latest` uses Server 2019 still. *Microsoft is making `2022` the value for `latest`. For more info see https://github.com/actions/virtual-environments/issues/4856.*
* Checkout version: `v2` (Latest version.)<br>Note: This can **not** be changed.
