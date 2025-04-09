# son_topish_python_boshlangich
#import random
#def sontop(x=100):
#    tasdofiy_son =random.randint(1, x)
#    print(f"Men 1 dan {x} gacha son o'yladim.Son topa olasizmi:")
#    taxminlar = 0
#    while True:
#        taxminlar += 1
#        taxmin = int(input(">>>>>"))
#        if taxmin>tasdofiy_son:
#            print("Siz yozgan son men o'ylagan sondan kotta.Yana bir harakat qilib ko'ring: ")
#        elif taxmin<tasdofiy_son:
#            print("Siz yozgan son men o'ylagan sondan kichik.Yana bir harakat qilib ko'ring: ")
#        else:
#            break
#    print("Tabriklayman {taxminlar} taxmin bilan men o'ylagan son topdingiz:!!!🤣")
#    return taxminlar
#
#def sontop_hp(x=100):
#    input(f"1 dan {x} gacha son o'ylang.Men topishga harakat qilaman:")
#    quyi=1
#    yuqori = x
#    taxminlar = 0
#    while True:
#        taxminlar += 1
#        if quyi != yuqori:
#            taxmin = random.randint(quyi, yuqori)
#        else:
#            taxmin = quyi
#        javob = input(f"Siz {taxmin} sonni o'yladizngiz adashmasam:to'g'ri(t)"
#                      f"Men o'ylagan son bundan kotta (+),yoki kichikroq (-):>> ".lower())
#        if javob == '-':
#           yuqori = taxmin - 1
#        elif javob == '+':
#            quyi = taxmin + 1
#        else:
#            break
#    print(f"{taxminlar} taxmin bilan topdimiii xaaaa san o'ylagan sonlarni🤣🤣 ")
#    return taxminlar
#
#def play(x=100):
#    yana = True
#    while yana:
#        taxminlar_user = sontop(x)
#        taxminlar_hp = sontop_hp(x)
#        if taxminlar_user<taxminlar_hp:
#            print("Siz yutdingiz")
#        elif taxminlar_user>taxminlar_hp:
#            print("Men yutdim xaaa")
#        else:
#            print("Durrang bo'ldi pidaraz")
#        yana =int (input("Yana o'ynashni hohlaysanmi.Agar o'ynashni hohlasang yes(1)/no(0) sonlardan birini tanlagin:"))

