mcmc = function(a,d,m,sd) {
  for(i in 1:a) {
    dta = rnorm(d,m,sd)
    dta2 = dta+1
    dta3 = cumprod(dta2)
    dta4 <- data.frame(dta4,dta3)
     matplot(dta4,type = "l",)
  }
}
mcmc(6,50,0,.05)
