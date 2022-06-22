# THIS IS A HEADER
## THIS IS A SECOND HEADER
###### THIS IS THE SMALL SUB HEADER

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

![image of dog](https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/golden-retriever-royalty-free-image-506756303-1560962726.jpg?crop=0.672xw:1.00xh;0.166xw,0&resize=640:*)

```


for (i in 1:length(amph_nome2)){
  
  amf <- paste("mapPR_", amph_nome2[i],sep="")
  amf2=eval(get(amf))[orden]
  values(r) = amf2
  writeRaster(r, filename = paste(amf,".asc", sep=""))
}

```
