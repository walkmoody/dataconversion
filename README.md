# dataconversion
We have tools which produce CSV documents listing hosts/endpoints and whether or not our security tools (SentinelOne, Huntress, etc.) are installed on the host. From this raw data, we need to create PDF reports for our clients listing what specific hosts are missing what specific security tool.

## Running

Install needed Python modules by executing the following from the command line:

```
pip install -r requirements.txt
```

To run the program use the command

```
python convert.py
```