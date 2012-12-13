# Mock Draft Central Data Exporter

Exports Mock Draft Central baseball ADP values in CSV format.

## Installation

```bash
$ pip install python-mdc-utils
```

## Usage

```bash
usage: download-mdc-adp [-h] -u USERNAME -p PASSWORD [--headers]

optional arguments:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        Mock Draft Central username
  -p PASSWORD, --password PASSWORD
                        Mock Draft Central password
  --headers             Include CSV headers in export
```

## Notes

- This app is hard-coded for baseball, mixed 5x5 only. It may not always be this way.
- Usage of this app requires a Mock Draft Central account.
