## Setup
At project root path, run `docker build . -f installer/Dockerfile -t max_kb:latest`
Then, run `docker run --name=maxkb -p 8080:8080 -v <path-on-host>:/var/lib/postgresql/data -it max_kb`

## Convert the run-maxkb.sh to unix format
The file was likely created on a Windows machine, hence it contains CRLF line endings. The file will need to be converted to unix format before execution. `dos2unix` is an option for this.

## Login after setup
```
User: admin
Password: MaxKB@123..
```

