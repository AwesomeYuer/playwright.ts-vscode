```shell
npm init playwright@latest --yes -- --quiet --browser=chromium --channel=msedge --gha

npx playwright install --force msedge

npx playwright open --browser=chromium --channel=msedge
```


[![Build Status](https://microshaoft.visualstudio.com/AzurePipelines/_apis/build/status/AwesomeYuer.playwright.ts-vscode?branchName=master)](https://microshaoft.visualstudio.com/AzurePipelines/_build/latest?definitionId=44&branchName=master)