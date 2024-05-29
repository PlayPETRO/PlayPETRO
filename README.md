input_list = [1, 2, 5, 7, 12, 11, 35, 4, 89, 10]
def pro(x):
    return x**2
def supra(x):
    return x % 2 !=0

result = list(map(pro, filter(supra, input_list)))

print(result)
