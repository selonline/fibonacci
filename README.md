# fibonacci
limit = int(input("Limit: "))
total = 0

list1 = [1,1]
for i in list1:
    if (total > limit):
        list1.pop()
        print(list1)
        break
    total = list1[len(list1)-2] + list1[len(list1)-1]
    list1.append(total)
