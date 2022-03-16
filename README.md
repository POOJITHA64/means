# means
print("Enter values in an array")
x<- scan()
sum<-0
for(i in 1:length(x))
  {
    sum=sum+x[i]
  }
meanvalue<-sum/length(x)
print("average value of the given values")
print(meanvalue)
print("mean value using built in function")
print(mean(x))
