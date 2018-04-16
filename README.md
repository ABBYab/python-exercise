#  第一个小游戏，猜数字游戏#aim=45
guss_aim=False
while guss_aim==False:
    guss = int(input("please enter a number !"))
    if guss >aim:
        print("the  number you entered is bigger than aim ,please try again ")
    if guss<aim:
        print("the  number you entered is smaller2 than aim ,please try again ")
    if guss==aim:
        guss_aim= True
        print("guss  right! ")
