**FUCC** :_package manager_

Fucc is a serverless _package manager_ based on bash

while it does not require servers. it does rely on "Repo" files these being

>.fucc

the strict formatting for a package in the repo file is

>[name] [url/ip] [hash] [dependencies,dependencies]
>
>[name] [url/ip] [hash] [dependencies,dependencies]
>
>[name] [url/ip] [hash] [dependencies,dependencies]
>
>...

**Dependencies**

curl,awk,grep,sed,column,sha256sum,shasum

just curl and GNU core utils




**Install**

>sudo curl -fsSL https://raw.githubusercontent.com/BananaFeals/FUCC/main/fucc -o /usr/local/bin/fucc && sudo chmod +x /usr/local/bin/fucc

**Pros**

super cheap to implement, doesnt require servers and hosting

**Cons**

I can not stress this enough its incredibly dangerous, not even the code. the system by nature is very dangerous

**License**

you dont even have to credit me. just use it
