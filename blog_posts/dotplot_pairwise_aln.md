
## Install `xsltproc`

```
sudo apt install xsltproc
```


## Run `xsltproc`

Link: https://github.com/lindenb/xslt-sandbox/blob/master/stylesheets/bio/ncbi/blast2dotplot.xsl

```
xsltproc --novalid  blast2dotplot.xsl   blastn.xml  > dotplot.html
```

