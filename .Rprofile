### Andy Hall
### R Profile file

### function to produce nice plots
### preserves most defaults through "..."
### defaults labels to blank, axes to missing, makes points look nice
plot.hall <- function(..., xlab="", ylab="", xaxt="n", yaxt="n", pch=21, bg="gray70") {
	plot(..., xlab=xlab, ylab=ylab, xaxt=xaxt, yaxt=yaxt, pch=pch, bg=bg)
}

### override default mgp in par to make better ticks
par.hall <- function(..., mgp=c(3,.5,0)) {
	par(..., mgp=mgp)
}

### Michael Gill's brilliant function to make transparent colors
makeTransparent<-function(someColor, alpha)
{
  newColor<-col2rgb(someColor)
  apply(newColor, 2, function(curcoldata){rgb(red=curcoldata[1], green=curcoldata[2],
                                              blue=curcoldata[3],alpha=alpha, maxColorValue=255)})
}

