# Theme for the Modernizing the M&A Workflow Series
The [Xaringan](https://github.com/yihui/xaringan) theme ([git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules)) for the Modernizing the M&A Workflow series ("mod-mAndA").

## Background
Xaringan Presentations ([see Yihui's demo](https://slides.yihui.name/xaringan/)), are HTML slides generated from R Markdown, created using the HTML slide library [remark.js](https://remarkjs.com).

Xaringan presentations [use themes](https://github.com/yihui/xaringan/wiki/Themes) to style the slide content of the web page. Available themes are listed using: 
```r 
names(xaringan:::list_css())
```
and can be used by specifying them in the .Rmd file's YAML header. 

## Description
This theme uses a customized version of the combined Kunoichi/Ninjutsu ["ninja" themes](https://github.com/emitanaka/ninja-theme) created by Emi Tanaka. Her demo is [here](https://emitanaka.org/ninja-theme/themes/kunoichi/kunoichi-theme-example.html).

This theme is a "[git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules)" inside of the [mAndA/mod-mAndA-template](https://esgovcloud.com/mAndA/mod-mAndA-template) repo.
