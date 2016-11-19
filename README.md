##Please see the out put listed below

> a <- makeCacheMatrix( matrix(c(1,2,3,4), nrow = 2, ncol = 2) );
> summary(a)
             Length Class  Mode    
setMatrix    1      -none- function
getMatrix    1      -none- function
cacheInverse 1      -none- function
getInverse   1      -none- function
> a$getMatrix()
     [,1] [,2]
[1,]    1    3
[2,]    2    4
> cacheSolve(a)
     [,1] [,2]
[1,]   -2  1.5
[2,]    1 -0.5
> cacheSolve(a)
getting cached data
     [,1] [,2]
[1,]   -2  1.5
[2,]    1 -0.5
