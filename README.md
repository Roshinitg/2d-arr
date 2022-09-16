r_num = int(input("Input no. of rows: "))
c_num = int(input("Input no. of columns: "))
multi_list = [[0 for col in range(c_num)] for row in range(r_num)]

for row in range(r_num):
    for col in range(c_num):
        multi_list[row][col]= row*col

print(multi_list)
