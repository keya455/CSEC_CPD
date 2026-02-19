n = int(input())
lst = list(map(int, input().split()))
count = 0
officer = 0
for i in lst:
    if i > 0:
        officer += i
    elif i == -1:
        if officer > 0:
            officer -= 1
        else:
            count += 1
print(count)
