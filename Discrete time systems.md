# Sample program 1
``` scilab

clc
clear
y(1)=10
for n=2:20
x(n)=0.4ˆ(n-2)
y(n)=x(n)+0.6*y(n-1);
end
n=[2:20]
y1=-2*(0.4)ˆ(n-2)+9*(0.6)ˆ(n-2)
plot(y)
plot(y1’)
```


# Sample program 2
``` scilab
y(1)=12
y(2)=0
x=ones(1,20)
for n=3:20
y(n)=4*x(n)+(1/6)*y(n-1)+(1/6)*y(n-2);
end
n=[3:20]
y1=-1.2*(0.5)ˆ(n-3)+1.2*(-1/3)ˆ(n-3)+6
disp(y)
```



# Sample program 3
``` scilab
x=[0 0 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0]
y(1)=0
y(2)=0
for n=1:16
y(n+2)= x(n+2)+0.166*y(n+1)+0.166*y(n)
end
disp(y)
plot(y)
```

