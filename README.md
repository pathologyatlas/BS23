




```
r language BS23, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis Crohn hastalığında fistül TR, echo = (language == "TR")
## BS23 - Crohn hastalığında fistül {#sec-BS23 }
```


```
asis Crohn disease fistule EN, echo = (language == "EN")
## BS23 - Crohn disease fistule {#sec-BS23 }
```






```
r BS23 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS23-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS23/HE.html",
  file = "./screenshots/BS23-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS23/HE.html](https://images.patolojiatlasi.com/BS23/HE.html)





```
asis, echo = (language == "TR")

**Crohn hastalığında fistül**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS23-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS23/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS23/HE.html)
```

```
asis, echo = (language == "EN")

**Crohn disease fistule**

[![Click for Full Screen WSI](./screenshots/BS23-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS23/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS23/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS23/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS23/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

Crohn hastalığında fistül

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

Crohn disease fistule

:::

```









:::::








