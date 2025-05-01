# SQLcl (SQL Developer Command Line)

Oracle **SQLcl** (SQL Developer Command Line) is a modern, free command-line interface for Oracle Database, serving as a lightweight alternative to SQLPlus. It allows you to execute SQL and PL/SQL interactively or run scripts in batch. **SQLcl** enhances productivity with features from Oracle SQL Developer, including in-line editing, tab completion, command history, command recall for a feature-rich experience, and support for running existing SQLPlus scripts.

https://www.oracle.com/database/sqldeveloper/technologies/sqlcl/

<br>

## Key Features

**In-Line Editor**

edit multi-line statements and scripts interactively at the SQLcl prompt

**Change Management**

native Liquibase integration, with automatic changelog generation for your Oracle Database objects


**Command History**

cycle through your 100 previous scripts/commands


**Completion Insight**

auto-complete object names or keywords using the tab key


**New Commands**

CTAS, DLL, Repeat, ALIAS, SCRIPT, FORMAT, and many more!



**Client Side Scripting**

execute javascript to manipulate query results, build dynamic commands, interact with the session, and much more


**SQL*Plus Support**

SQL*Plus environment settings, commands, and behaviors



<br>


## Download

- <a href="https://www.oracle.com/database/sqldeveloper/technologies/sqlcl/download/">Downloads</a>
- <a href="https://download.oracle.com/otn_software/java/sqldeveloper/sqlcl-latest.zip">Latest version update</a>

<br>

## Install Oracle SQLcl & Connect on Database

<br>

```shell
sudo java --version
```

```shell
which java
```

```shell
cd /<$FILE_PATH>/sqlcl/bin
```

```shell
./sql <$USER_NAME>/<$PASSWORD>@<$HOST>:<$PORT>/<$SID>
```

<br>

### Install Oracle SQLcl with Brew (Homebrew)


```shell
brew install --cask sqlcl
```
https://formulae.brew.sh/cask/sqlcl

<br>

## Start SQLcl

```shell
./sql
```

```shell
./sql /nolog
```
<br>

## Create a symbolic link (symlink)

### Add to PATH
```shell
export PATH="$PATH:<Your Path>/sqlcl/bin"
```

### Create symlink
```shell
sudo ln -s <Your Path>/sqlcl/bin /usr/local/bin/sql
```

### Start SQLcl
```shell
sql ${username}/${password}@localhost:1521/FREE as sysdba
```

<br>

## SQLcl Documentation

- <a href="https://docs.oracle.com/en/database/oracle/sql-developer-command-line/">Release Documentation</a>
- <a href="https://docs.oracle.com/en/database/oracle/sql-developer-command-line/20.2/sqcug/working-sqlcl.html#GUID-DB0D123B-AFA1-4C5A-AB2A-A7B59863C9B9">Command-Line Reference</a>
- <a href="https://www.oracle.com/database/technologies/appdev/sqlcl/sqlcl-faq.html">FAQ</a>
- <a href="https://www.oracle.com/tools/sqlcl/sqlcl-relnotes-202.html">Release Notes</a>
