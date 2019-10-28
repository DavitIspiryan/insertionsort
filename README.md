# insertionsort

def insertion_sort(A):
    for i in range(1, len(A)):
        for j in range(i-1, 0, -1):
            if A[J] > A[J+1]:
                A[J], A[J+1] = A[J+1], A[J]
            else:
                Break


def insertion_sort(A):
    for i in range(1, len(A)):
        CurNum= A[i]
        for J in range(i-1, 0, -1):
            if A[J] > curNum:
                A[J+1] = A[J]
            else:
                A[J+1] = curNum
                break
