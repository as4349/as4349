- π Hi, Iβm @as4349
- π Iβm interested in ...
- π± Iβm currently learning python.
- ποΈ Iβm looking to advisor on ...
- π« How to reach me ...

<!---
as4349/as4349 is a β¨ special β¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- Recently, I've been making tamagochi(pypet).
- but.... It's hard make to program 
- So.... a....
- Could you give me some advice after watching what I make? 

#λ€μν μμ΄ν 
from item import *
#κ³ μμ΄μ μν
from emo import *

act = ""
#####################################μμλ¨ΉκΈ°μΌ
def act2():
    act2 = ""
    while act2 != 'X':
            print(nomal2)
            act2 = input("μ΄λ€ κ²μ λ¨Ήμ΄κ³  μΆμ΅λκΉ?\n"+"1.μμ  2.μ¬ν 3.κ½ 4.λ€λ‘κ°κΈ°")
            print("λΉμ μ %sμκ² μμμ μ£Όλ €ν©λλ€..\n"%Pname)
            if act2 == '1' or act2 == 'μμ ':
                print (happy+fish,"\n\n")
                print ("λΉμ μ %sμκ² μμ μ μ€¬μ΅λλ€..\n"%Pname,"%sλ λ§μκ² λ¨Ήμμ΅λλ€..\n"%Pname)            
            elif act2 == 'κ½' or act2 == '3':
                print (angry+flower,"\n")
                print ("%sλ κ½μ λ¨Ήμ μ μλκ² κ°μ΅λλ€. \n"%Pname)
            elif act2 == 'μ¬ν' or act2 == '2':
                print (upfeel+candy,"\n")
                print("%sλ λ¬μ½€ν μΊ£λ’μ¬νμ λ³΄κ³  λͺΉμ κΈ°λΆ μ’μκ²κ°μ΅λλ€. \n"%Pname)
            elif act2 == '4' or act2 == 'λ€λ‘κ°κΈ°' :
                print(act)
                break
            else :
                print(nomal2)
                print("μ£Όμ΄μ§ λ³΄κΈ°μ€μμ κ³¨λΌμ£ΌμΈμ.\n")
#
next1 = "λ€μμ λ¬΄μμ ν κΉμ?\n"

#μ²μ μμνμλ
print (nomal)
Pname = input("κ³ μμ΄μ μ΄λ¦μ μ§μ΄μ£ΌμΈμ.\n\n")
print("λΉμ μ΄ μ§μ΄μ€ κ³ μμ΄μ μ΄λ¦μ %s μλλ€.\n\n"%Pname)
print (happy+"\nμ΄λ¦μ΄ μκΈ΄ %sλ κΈ°λ»νλκ² κ°μ΅λλ€.\n\n"%Pname)
print (nomal)

# νλ
while act != 'X':
    act = input("λ¬΄μμ νμκ² μ΅λκΉ? 1.μμμ£ΌκΈ° 2.λ§κ°λ₯΄μΉκΈ° 3.μ»κ²¨μ£ΌκΈ° λκ°μλ €λ©΄ X : \n").upper()
    if act == '1' or act == 'μμμ£ΌκΈ°' :
        act2()
        print("λ€μμ λ¬΄μμ ν κΉμ?\n")
    elif act == '2' or act == 'μ°λ€λ¬κΈ°':
        print(nomal)
        print("λΉμ μ %sλ₯Ό μ°λ€λ¬μ΄ μ£Όμμ΅λλ€..\n"%Pname)
        print("%sλ λΉμ μ λ°λΌλ³΄κ³  μμ΅λλ€..\n"%Pname)
    elif act == '3' or act == 'μ°λ€λ¬κΈ°':
        print(angry)
        print("%sλ λͺ©μμ λ³λ‘ μ’μνμ§ μλ κ² κ°μμμ~.\n"%Pname)
    elif act == 'X' or act == 'λκ°κΈ°' :
        print(sad+"λμ€μΉ...μκ°....\n")
        exit()
        break
    else :
        print("λ€μ μλ ₯ν΄μ£ΌμΈμ\n") 
