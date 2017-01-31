# ProgrammingAssignment2
#test functions by giving example
> test_matrix<-makeCacheMatrix(matrix(1:4,2,2))
> test_matrix$get()
     [,1] [,2]
[1,]    1    3
[2,]    2    4
> test_matrix$getInverse()
NULL
cacheSolve(test_matrix)
     [,1] [,2]
[1,]   -2  1.5
[2,]    1 -0.5
test_matrix$getInverse()
     [,1] [,2]
[1,]   -2  1.5
[2,]    1 -0.5
#Another example:
 test<-makeCacheMatrix(matrix(c(1,3,5,7),2,2))
> test$get()
     [,1] [,2]
[1,]    1    5
[2,]    3    7
> cacheSolve(test)
       [,1]   [,2]
[1,] -0.875  0.625
[2,]  0.375 -0.125
> test$getInverse()
       [,1]   [,2]
[1,] -0.875  0.625
[2,]  0.375 -0.125
