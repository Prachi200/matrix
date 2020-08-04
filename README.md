# matrix
Matrix operations using python.
row=int(input("enter the rows you want:"))
col=int(input("enter the columns you want:"))
matrix1=[[int(input())for i in range(col)] for j in range(row)]
for i in range(row):
    for j in range(col):
        print(format(matrix[i][j],"<3"),end="")
    print()    
matrix2=[[int(input())for i in range (col)] for j in range(row)]
for i in range(row):
    for j in range(col):
        print(format(matrix[i][j],"<3"),end="")
    print()
result=[[o for i in range (col)]for j in range (row)]
for i in range(row):
    for j in range (col):
        result=matrix1[i][j]+matrix2[i][j]
for i in range (row):
    for j in range(col):
        print(format(result[i][j]),"<3"),end="")
print()
