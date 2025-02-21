# vrest-ng-cli

This repository is just an npm wrapper around `vrest-ng-cli` binary. `vrest-ng-cli` is a command line utility aim to perform various tasks through command line. As of now, it provides two commands:
1. **Run Command**
	1. Executes test cases on command line, which are created by [vREST NG](https://vrest.io).
	2. Run command can be used in any third party schedular like cron to schedule test cases.
	3. Run command can be used in any continuous integration server like Jenkins, TeamCity, Azure Devops, CircleCI, TravisCI etc.

2. **Import Command**
	1. Import command is helpful in importing test data from various sources like vREST Cloud, Postman, Swagger.
	2. Import command can also be used in updating the swagger schema definitions in the project.

## For NodeJS projects
1. Simply install the module `vrest-ng-cli` as a dev dependency to your project by using the following commands:
```
$ cd /path/to/your/project
$ npm install vrest-ng-cli --save-dev
```
Note: Please note that the `vrest-ng-cli` npm module is wrapper around vrest-ng-cli binary. The package version determines the version of the downloaded binary.

## For projects which don't use NodeJS or npm
Simply download the binary from the table below:
### Download:

| Version | Linux | Mac OS | Windows | Alpine |
| ------------- | ------------ | ------------| ----------- | ----------- |
| 2.5.4 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.4/vrest_ng_cli_linux_2_5_4) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.4/vrest_ng_cli_mac_2_5_4) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.4/vrest_ng_cli_win_2_5_4.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.4/vrest_ng_cli_alpine_2_5_4) |
| 2.5.1 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.1/vrest_ng_cli_linux_2_5_1) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.1/vrest_ng_cli_mac_2_5_1) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.1/vrest_ng_cli_win_2_5_1.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.1/vrest_ng_cli_alpine_2_5_1) |
| 2.5.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.0/vrest_ng_cli_linux_2_5_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.0/vrest_ng_cli_mac_2_5_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.0/vrest_ng_cli_win_2_5_0.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.5.0/vrest_ng_cli_alpine_2_5_0) |
| 2.4.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.4.0/vrest_ng_cli_linux_2_4_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.4.0/vrest_ng_cli_mac_2_4_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.4.0/vrest_ng_cli_win_2_4_0.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.4.0/vrest_ng_cli_alpine_2_4_0) |
| 2.3.2 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.2/vrest_ng_cli_linux_2_3_2) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.2/vrest_ng_cli_mac_2_3_2) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.2/vrest_ng_cli_win_2_3_2.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.2/vrest_ng_cli_alpine_2_3_2) |
| 2.3.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.0/vrest_ng_cli_linux_2_3_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.0/vrest_ng_cli_mac_2_3_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.0/vrest_ng_cli_win_2_3_0.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.3.0/vrest_ng_cli_alpine_2_3_0) |
| 2.1.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.1.0/vrest_ng_cli_linux_2_1_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.1.0/vrest_ng_cli_mac_2_1_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.1.0/vrest_ng_cli_win_2_1_0.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.1.0/vrest_ng_cli_alpine_2_1_0) |
| 2.0.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.0.0/vrest_ng_cli_linux_2_0_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.0.0/vrest_ng_cli_mac_2_0_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v2.0.0/vrest_ng_cli_win_2_0_0.exe) | |
| 1.9.2 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.9.2/vrest_ng_cli_linux_1_9_2) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.9.2/vrest_ng_cli_mac_1_9_2) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.9.2/vrest_ng_cli_win_1_9_2.exe) |[Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.9.2/vrest_ng_cli_alpine_1_9_2) | 
| 1.8.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.8.0/vrest_ng_cli_linux_1_8_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.8.0/vrest_ng_cli_mac_1_8_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.8.0/vrest_ng_cli_win_1_8_0.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.8.0/vrest_ng_cli_alpine_1_8_0) |
| 1.7.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.7.0/vrest_ng_cli_linux_1_7_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.7.0/vrest_ng_cli_mac_1_7_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.7.0/vrest_ng_cli_win_1_7_0.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.7.0/vrest_ng_cli_alpine_1_7_0) |
| 1.6.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.6.0/vrest_ng_cli_linux_1_6_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.6.0/vrest_ng_cli_mac_1_6_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.6.0/vrest_ng_cli_win_1_6_0.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.6.0/vrest_ng_cli_alpine_1_6_0) |
| 1.5.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.5.0/vrest_ng_cli_linux_1_5_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.5.0/vrest_ng_cli_mac_1_5_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.5.0/vrest_ng_cli_win_1_5_0.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.5.0/vrest_ng_cli_alpine_1_5_0) |
| 1.4.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.4.0/vrest_ng_cli_linux_1_4_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.4.0/vrest_ng_cli_mac_1_4_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.4.0/vrest_ng_cli_win_1_4_0.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.4.0/vrest_ng_cli_alpine_1_4_0) |
| 1.2.3 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.3/vrest_ng_cli_linux_1_2_3) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.3/vrest_ng_cli_mac_1_2_3) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.3/vrest_ng_cli_win_1_2_3.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.3/vrest_ng_cli_alpine_1_2_3) |
| 1.2.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.0/vrest_ng_cli_linux_1_2_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.0/vrest_ng_cli_mac_1_2_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.0/vrest_ng_cli_win_1_2_0.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.2.0/vrest_ng_cli_alpine_1_2_0) |
| 1.0.4 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.4/vrest_ng_cli_linux_1_0_4) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.4/vrest_ng_cli_mac_1_0_4) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.4/vrest_ng_cli_win_1_0_4.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.4/vrest_ng_cli_alpine_1_0_4) |
| 1.0.3 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.3/vrest_ng_cli_linux_1_0_3) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.3/vrest_ng_cli_mac_1_0_3) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.3/vrest_ng_cli_win_1_0_3.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.3/vrest_ng_cli_alpine_1_0_3) |
| 1.0.1 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.1/vrest_ng_cli_linux_1_0_1) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.1/vrest_ng_cli_mac_1_0_1) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.1/vrest_ng_cli_win_1_0_1.exe) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.1/vrest_ng_cli_alpine_1_0_1) |
| 1.0.0 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.0/vrest_ng_cli_linux_1_0_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.0/vrest_ng_cli_mac_1_0_0) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v1.0.0/vrest_ng_cli_win_1_0_0.exe) ||
| 0.8.4 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.4/vrest_ng_cli_linux_0_8_4) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.4/vrest_ng_cli_mac_0_8_4) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.4/vrest_ng_cli_win_0_8_4.exe) ||
| 0.8.2 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.2/vrest_ng_cli_linux_0_8_2) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.2/vrest_ng_cli_mac_0_8_2) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.2/vrest_ng_cli_win_0_8_2.exe) ||
| 0.8.1 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.1/vrest_ng_cli_linux_0_8_1) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.1/vrest_ng_cli_mac_0_8_1) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.8.1/vrest_ng_cli_win_0_8_1.exe) ||
| 0.5.3 | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.5.3/vrest_runner_linux_0_5_3) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.5.3/vrest_runner_mac_0_5_3) | [Download](https://github.com/Optimizory/vrest-ng-cli/releases/download/v0.5.3/vrest_runner_win_0_5_3.exe) ||

### Setup / Installation:

1.  **For Windows Machine**
	1. This exe file can be executed on command prompt. So, double mouse click on the downloaded file will not help in executing the test cases.  
	2. First, move the downloaded binary file to the directory of your choice
	3. Rename the binary file to just vrest-ng-cli with the following command:
  
    `C:\dir\path> move vrest_ng_cli_win_x_y_z.exe vrest-ng-cli.exe`
    
	4. `Optional` Now add this binary file in your execution path by setting the environment variable PATH.

2.  **For Linux / Mac Machine**
	1. First, move the downloaded binary file to the directory of your choice
	2. Rename the binary file to just vrunner with the following command:

    `$ mv vrest_ng_cli_linux_x_y_z vrest-ng-cli`

	3. Make it executable by executing the following command:

    `$ chmod +x vrest-ng-cli`

	4. Now add this binary file in your execution path.

## Import Command

This is the command used to import test cases into vREST NG.

### Usage Instructions
```bash
vrest-ng-cli import --projectdir="<path_to_project_directory>"
	--source="<import_source>"
	--sourcefile="<source_file_path>"
	[--defaulttestsuite="<test_suite_name>"]
	[--updateonly="<true_or_false>"]
```
### Example
```bash
vrest-ng-cli import --source="swagger"
	--sourcefile="/path/to/your/swagger/file.json|yaml"
	--projectdir="/path/to/your/project/directory"
	--defaulttestsuite="Sample\ Test\ Suite"
	--updateonly="true"
```

### Options
```bash
--help              : Show help
--source            : Import Source [required]
                        [choices: "vrest-cloud", "swagger", "postman"]
--sourcefile        : Provide the source file path which you want to import.
--projectdir        : Provide the path of the project directory in you want to
                      import/re-import the data. [required]
--defaulttestsuite  : Provide the default test suite name.
--updateonly        : Set this option if you want to update the test data instead of 
                      creating again. This option is applicable only for swagger source 
                      as of now. [default: false]
```

## Run Command
This is the command used for running the test cases that you stored in the project directory.

### Usage Instructions
```bash
vrest-ng-cli run --projectdir="<path_to_tc_directory>"
	[--testsuites="<comma_separated_test_suite_names>"]
	[--tags="<comma_separated_tag_names>"]
	[--env=<environment_name>] 
	[--nosslcheck=<boolean_value>]
	[--consoleLogging=<boolean_value>]
	[--logger=<one_of_available_loggers>]
	[--logfilepath="<path_of_log_file_for_logger>"]
  [--record=<boolean_value>]
  [--token=<cli_token>]
```

### Example
```bash
vrest-ng-cli run --projectdir="/path/to/your/project/directory"
	--testsuites="Sample\ Test\ Suite"
	--logger=xunit
	--logfilepath="/path/to/directory/for/vrest-logs/logs.xml"
```
And if you would like to record the test execution results in the vREST NG Dashboard Service then
```bash
vrest-ng-cli run --projectdir="/path/to/your/project/directory"
  --testsuites="Sample\ Test\ Suite"
  --logger=xunit 
  --logfilepath=/path/to/directory/for/vrest-logs/logs.xml
  --record=true
  --token="paste the generated CLI Token here"
```
Note: For information on generating CLI Token, you may look at our guide on [CLI Token](https://vrest.io/docs/dashboard/cli-token.html)

### Options:
```bash
--projectdir      : Provide the path of the project directory which contains
                    the testsuites.json file. If you dont provide any filter, 
                    then it will execute all the testcases available in the project.
--testsuites      : Optional Filter: Provide the comma separated list of test
                    suite names which you want to execute in double quotes.
--tags            : Optional Filter: Provide the comma separated list of tags
                    which you want to execute in double quotes.
--methods         : Optional Filter: Provide the comma separated list of method
                    names which you want to execute in double quotes.
--exclude-testsuites: Optional exclude filter: Provide the comma separated
                      list of test suite ids which you don't want to execute
                      in double quotes.
--exclude-tags    : Optional exclude filter: Provide the comma separated
                    list of tags which you don't want to execute in double
                    quotes.
--exclude-methods : Optional exclude filter: Provide the comma separated
                    list of method names which you don't want to execute in
                    double quotes.
-T, --timeout     : How much to wait for response after execution of test case.
                    It should be provided in unit of seconds.
                    e.g. -T=3 will wait for 3 seconds for response
-N, --env         : Provide the environment name to initialize the global 
                    variables. By default environment `Default` is used.
--vars, -v        : Provide extra run time variables through this option
                    apart from `--env` option.                 [default: {}]
--envfilepath     : Provide the environment file path containing extra run
                    time variables (key/value pairs) in JSON format.
--token           : Provide the authentication token to store the test 
                    run results on vREST NG Dashboard Service.
--record          : If this argument is `true`, then the runner will
                    record and store the test run results in vREST NG
                    Dashboard Service.     [boolean] [default: false]
-S, --nosslcheck  : If this argument is `true`, vRUNNER will process all 
                    requests, without Secure Certificate Check. By default 
                    Secure Certificate Check is enabled. This option is useful 
                    in self-signed certificate issues.
-C, --consoleLogging: If this argument is `false`, then the runner will not
                    log the results on console.
-L, --logger      : Your desired logging of the runner execution process 
                    and result. This can be either `json` or `csv` 
                    or `xunit` or `custom`. By default `console` logger is used.
-F, --logfilepath : Valid if other than `console` logger is selected.
                    Absolute path of the log file, into which execution process 
                    and result logs will be dumped.
                    If path/file is not present, tool will try to setup that path, 
                    and create file automatically.
                    Please note that if file already exists, that will be overwritten.
                    By default it will be the `vrest_logs/logs.[json|xml|csv]` in 
                    current directory.
--logscriptpath   : Valid if logger value is `custom`. Provide file path of
                    the logger script to generate custom formatted output.
--stoponerror     : Specify -1 if you want to skip the current test suite on error. 
                    Specify 0 if you don't want to stop on error. Specify 1
                    if you want to stop on first error. Otherwise specify
                    any number if you want to stop the execution after the
                    specified number of failed executions.     [default: 0]
--proxy           : If this argument is `true`, then the runner will respect the 
                    proxy related environment variables HTTP_PROXY, HTTPS_PROXY. 
                    Otherwise it will not use the proxy settings. [boolean] [default: true]
--help            : To see this help.
```

**Note:**
1. For more information on how you may write a custom logger to generate customized output, you may follow our guide on [custom logger](https://vrest.io/docs/cli/custom-logger.html).
2. For more information on providing run time variables through option `--vars` or `--envfilepath`, you may follow our guide on [run time variables](https://vrest.io/docs/cli/run-time-variables.html).
