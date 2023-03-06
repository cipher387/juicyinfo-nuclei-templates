# Juicy Info Extraction Nuclei Templates
Nuclei (https://github.com/projectdiscovery/nuclei) templates for extracting juicy info from web pages


Using Nuclei for OSINT. 5 minutes guide.

https://medium.com/@cyb_detective/using-nuclei-for-osint-5-minute-basic-guide-f8764424902b

How regular expressions can be useful in OSINT. Theory and some practice using Google Sheets

https://medium.com/@cyb_detective/this-article-consists-of-three-short-parts-31d31efabd5


Before launching, copy the juicy_info folder into the Nuclei directory and add some links to the links to the urls.txt file.


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


## Emails extractor

```console
nuclei -t juicy_info/email.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/email.png)

## Facebook links extractor

```console
nuclei -t juicy_info/facebook.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/facebook.png)


## Github links extractor

```console
nuclei -t juicy_info/github.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/github.png)



## Google Documents links extractor

```console
nuclei -t juicy_info/googledocuments.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/googledocument.png)



## Gravatar avatars links extractor

```console
nuclei -t juicy_info/gravatar.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/gravatar.png)





## Ipv4 extractor

```console
nuclei -t juicy_info/ipv4.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/ipv4.png)


## Linkedin links extractor

```console
nuclei -t juicy_info/linkedin.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/linkedin.png)


## Possible nickname handlers extractor

```console
nuclei -t juicy_info/nickname.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/nickname.png)


## Office documents links extractor

```console
nuclei -t juicy_info/officedocument.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/officedocuments.png)



## PDF documents links extractor

```console
nuclei -t juicy_info/pdf.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/pdf.png)



## Possible phone numbers extractor

```console
nuclei -t juicy_info/phonenumber.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/phonenumber.png)


## Telegram links extractor

```console
nuclei -t juicy_info/telegram.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/telegram.png)


## Twitter links extractor

```console
nuclei -t juicy_info/twitter.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/twitter.png)


## Links extractor

```console
nuclei -t juicy_info/twitter.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/url.png)


## YouTube links extractor

```console
nuclei -t juicy_info/youtube.yaml -l urls.txt
```

![image](https://github.com/cipher387/juicyinfo-nuclei-templates/blob/main/images/youtube.png)



# Run scanning with all templates


```console
nuclei -t juicy_info -l urls.txt
```













