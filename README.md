# Linear-Search-Optimization

#include <stdio.h>
// Linearly search x in arr[]. If x is present then return the index,
// otherwise return -1
int search(int arr[], int n, int x)
{
 int i;
 for (i=0; i<n; i++)
 {
 if (arr[i] == x)
 return i;
 }
 return -1;
}

