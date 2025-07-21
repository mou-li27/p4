# p4
matrix = [
    [0, 1, 2],
    [3, 0, 0],
    [4, 5, 0]
]


zero_count = 0


for i in range(len(matrix)):
    for j in range(len(matrix[0])):
        if matrix[i][j] == 0:
            zero_count += 1

print("Total number of zeroes in the matrix:", zero_count)
