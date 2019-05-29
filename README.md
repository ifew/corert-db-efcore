# Example C# .NET Core Runtime (CoreRT) with connect MySQL via EFCore Library

## WARNING

This example to implement code and I don't know result because its very long time to compile, you can help me to optimize rd.xml

## Preparing

1. Import Database from database.sql
2. Edit config database "configDB" in Program.cs

## NOTE

I think it's bug from Dapper or System.Data.SqlClient, Because I can use only runtime netcoreapp3.0 on Linux and MySqlConnector library. can't on MacOS, netcoreapp2.2 and official MySQL Connector 


## Command for run
```bash
$ sh run.sh [Runtime]
```

Example for MacOS
```bash
$ sh run.sh osx-64
```

Example for Linux
```bash
$ sh run.sh linux-64
```

Example for Windows
```bash
$ sh run.sh win-64
```

## System Require for Linux

- `sudo apt-get install clang-3.9`
- `sudo apt-get install libunwind-dev`
- `sudo apt-get install libcurl4-openssl-dev`
- `sudo apt-get install zlib1g-dev`
- `sudo apt-get install libkrb5-dev`
- `export CppCompilerAndLinker=clang-3.9`