# dbf2sql

## A simple tool written in Go to convert dBase DBF to SQL

### Installation

You'll need [Go](https://golang.org) installed on your system to install this program.

Once you have a functional Go toolchain, run the following command to install dbf2sql:

```bash
go get github.com/ShinoYasx/dbf2sql
```

### Usage

If you run the command `dbf2sql` without any parameters, you'll get the help:

```bash
$ dbf2sql
Usage of dbf2sql:
  -e string
        Encoding (default "UTF8")
  -f string
        dBase DBF file (required)
  -o string
        Output SQL file ('-' for stdout) (default "-")
  -t string
        Table name (required)
```

#### Example

```bash
dbf2sql -f base.dbf -o base.sql -t test
```
