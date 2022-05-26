# python_code
my python practice


# f=open('isa.txt','w')
# f.write('i am ishita\n')
# f.write('i love shivam')
# f.close()

# f=open('isa.txt','a')      # to append 
# f.write('varanasi')
# f=open('isa.txt','r')
# print(f.read())
# f.close()

# f=open('isa.txt','r')
# print(f.read(6))
# print(f.readline(),end='')  # only one line will come as output
# print(f.readlines())        # all lines will come as output in form of string

# f=open('isa.txt','r')
# for i in f:
#     print(i,end='')       # to read entire text file by using loop

# f=open('isa.txt','r')
# print(f.read())
# s=0
# for i in f:
#     s+=1              # it read any specific line
#     if s==3:
#      print(i)


# f=open('isa.txt','r')
# l=open('abc.txt','w')
# for i in f:               # to copy text from one file to another file
#     l.write(i)
# l=open('abc.txt','r')
# print(l.read())   

 
# f=open('abc.txt','r')
# n=0
# for i in f:        # to count no.of lines in txt file
#     n+=1
# print(n)

# f=open('abc.txt','r')
# n=0
# for i in f:
#     a=len(i.split())
#     n+=a                # to count no. of words in text file
# print(n,a)

f=open('ishita.txt','w')
f.write('''
my name is ishita
i am from varanasi
curentelly i am studing btech at gla
''')
f.close()
# f=open("ishita.txt",'r')
# print(f.readlines()[-2:])


# f=open('ishita.txt','r')
# l=[]
# for i in f:
#     l.append(i)
# print(l)

# c=f.read()
# print(c)

# f=open('ishita.txt','r')
# c=''
# for i in f:
#     c+=i
# print(c)

# f=open('ishita.txt','r')
# b=[]
# a=f.read()
# b=a.split()
# c=b[0]
# for i in b:
#      if len(c)<len(i):
#       c=i
# print(c)


