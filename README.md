<pre>
while True:
        n=int(input("enter number:"))
        i=1
        while (i<11):
            print(n,"X",i,"=",n*i)
            i+=1
        ans=input("do you wish to continue :(yes or no)... ")
        if(ans=='no'):
            print("come back again")
            break
            
