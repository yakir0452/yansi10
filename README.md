# yansi10
10def chunk(my_list, size):
    return [my_list[i:i+size] for i in range(0,len(my_list), size)]
my_list = [1, 2, 3, 4, 5, 6]
chunk(my_list, 2) # [[1, 2], [3, 4], [5, 6]]

