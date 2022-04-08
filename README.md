# amina
12345
orders = {
 'tea': 200,
 'burger': 56,
 'fruits': 25,
    'Coffee': 14
}
sorted_dic= sorted(orders.items(), key=lambda x: x[1])
print(sorted_dic)  # [('Coffee', 14), ('pepsi', 25), ('burger', 56), ('pizza', 200)]
