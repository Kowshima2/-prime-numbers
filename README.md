# -prime-numbers
print("Prime numbers from 15 to 25 are:")

for num in range(15, 26):
    if num > 1:
        for i in range(2, num):
            if num % i == 0:
                break
        else:
            print(num)

output:
Prime numbers from 15 to 25 are:
17
19
23
