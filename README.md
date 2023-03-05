# Juicy Info Extraction Nuclei Templates
Nuclei (https://github.com/projectdiscovery/nuclei) templates for extracting juicy info from web pages




## Airtables links extractor

```console
nuclei -t juicy_info/airtable.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/airtable.png)


## Bitcoin addresses links extractor

```console
nuclei -t juicy_info/bitcoin_address.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/bitcoin_addresses.png)
