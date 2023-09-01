# Complementary-strand-in-DNA
# cook your dish here
for t in range (int(input())):
    a = int(input())
    b = str(input())
    for i in b:
        if(i == "A"):
            print("T",end="")
        elif(i == "T"):
            print("A" ,end="")
        elif(i == "C"):
            print("G" ,end="")
        elif(i == "G"):
            print("C" ,end="")
    print()
