# EXPERIMENT-2
#q1

x = -5:0.5:5;
y1 = x.^2;
y2 = x.^3;
y3 = exp(x);
y4 = sin(x).*cos(x);
hold on;
plot(y1,x,"y");
plot(y2,x,"r");
plot(y3,x,"b");
plot(y4,x,"g");
xlabel("range");
ylabel("y");
