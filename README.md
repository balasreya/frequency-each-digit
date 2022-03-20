#frequency of each digit
x <- scan()
c <- vector()
while(x>0) {
  r=x%%10
  c <- append(c,r)
  x=x%/%10
}
c
c <- rev(c)
c

