- 👋 Hi, I’m @as4349
- 👀 I’m interested in ...
- 🌱 I’m currently learning python.
- 💞️ I’m looking to advisor on ...
- 📫 How to reach me ...

<!---
as4349/as4349 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- Recently, I've been making tamagochi(pypet).
- but.... It's hard make to program 
- So.... a....
- Could you give me some advice after watching what I make? 

#다양한 아이템 
from item import *
#고양이의 상태
from emo import *

act = ""
#####################################음식먹기야
def act2():
    act2 = ""
    while act2 != 'X':
            print(nomal2)
            act2 = input("어떤 것을 먹이고 싶습니까?\n"+"1.생선 2.사탕 3.꽃 4.뒤로가기")
            print("당신은 %s에게 음식을 주려합니다..\n"%Pname)
            if act2 == '1' or act2 == '생선':
                print (happy+fish,"\n\n")
                print ("당신은 %s에게 생선을 줬습니다..\n"%Pname,"%s는 맛있게 먹었습니다..\n"%Pname)            
            elif act2 == '꽃' or act2 == '3':
                print (angry+flower,"\n")
                print ("%s는 꽃을 먹을 수 없는것 같습니다. \n"%Pname)
            elif act2 == '사탕' or act2 == '2':
                print (upfeel+candy,"\n")
                print("%s는 달콤한 캣닢사탕을 보고 몹시 기분 좋은것같습니다. \n"%Pname)
            elif act2 == '4' or act2 == '뒤로가기' :
                print(act)
                break
            else :
                print(nomal2)
                print("주어진 보기중에서 골라주세요.\n")
#
next1 = "다음엔 무엇을 할까요?\n"

#처음 시작했을때
print (nomal)
Pname = input("고양이의 이름을 지어주세요.\n\n")
print("당신이 지어준 고양이의 이름은 %s 입니다.\n\n"%Pname)
print (happy+"\n이름이 생긴 %s는 기뻐하는것 같습니다.\n\n"%Pname)
print (nomal)

# 행동
while act != 'X':
    act = input("무엇을 하시겠습니까? 1.음식주기 2.말가르치기 3.씻겨주기 나가시려면 X : \n").upper()
    if act == '1' or act == '음식주기' :
        act2()
        print("다음엔 무엇을 할까요?\n")
    elif act == '2' or act == '쓰다듬기':
        print(nomal)
        print("당신은 %s를 쓰다듬어 주었습니다..\n"%Pname)
        print("%s는 당신을 바라보고 있습니다..\n"%Pname)
    elif act == '3' or act == '쓰다듬기':
        print(angry)
        print("%s는 목욕을 별로 좋아하지 않는 것 같아요요~.\n"%Pname)
    elif act == 'X' or act == '나가기' :
        print(sad+"냐오옹...잘가....\n")
        exit()
        break
    else :
        print("다시 입력해주세요\n") 
