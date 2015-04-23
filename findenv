function env=findenv(data,Fs,f)
start=find(data==max(data));
env=[];
env(1)=a(start);
i=start;
n=2;
per=floor(Fs/f);
while i<=length(t)-per
    envi(n)=find(data==max(data(i:i+per)));
    env(n)=a(envi(n));
    n=n+1;
    i=i+per;
end
env=10*log10(env);
end
