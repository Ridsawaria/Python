# Python


# Online IDE - Code Editor, Compiler, Interpreter

los = ("English","Maths","Science")

name = input("Enter Name:")
i = 0
sum =[]
high = []
res = {}
p = 0
while(i<3):
    m = []
    j = 0
    count = 0
    h = 0
    print(los[i])
    while(j<3):
        mark = int(input("Enter Your marks"))
        if(mark > h):
            h = mark
        m.append(mark)
        count = count + mark
        j = j + 1
    res[los[i]] = m
    if(count > 50):
        p = p + 1
    sum.append(count)
    high.append(h)
    i = i + 1
print(sum)
print(res)

print(name,los[0],sum[0],los[1],sum[1],los[2],sum[2],los[0],high[0],los[1],high[1],los[2],high[2])
if(p > 2):
    print("Pass")



