# plotsquared-diff

This repository tracks API and source code changes between major PlotSquared releases. 

- The `api-diff/` folder contains API differences generated using [japicmp](https://github.com/siom79/japicmp).
- The `source-diff/` folder contains full source code differences generated using [diff2html](https://github.com/rtfpessoa/diff2html-cli) using the following command:  
```sh
git diff v6..v7 > full.diff &&
diff2html -F output.html --title "PlotSquared source diff between v6 and v7" -i file -- full.diff
```

You can view the output [here](https://intellectualsites.github.io/plotsquared-diff/).
