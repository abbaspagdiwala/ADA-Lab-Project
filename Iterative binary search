#include <iostream>
using namespace std;

int binarySearch(int array[], int x, int low, int high) {
  
    // Repeat until the pointers low and high meet each other
  while (low <= high) {
    int mid = low + (high - low) / 2;

    if (array[mid] == x)
      return mid;

    if (array[mid] < x)
      low = mid + 1;

    else
      high = mid - 1;
  }

  return -1;
}

int main(void) {
  int array[5];
  int n;
  int x;
  cout<<"\n Input Array : \n";
  for(int i=0;i<5;i++)
  {
  	cin>>array[i];
  }
  cout<<"\n Enter element to search : ";
  cin>>x;
  int result = binarySearch(array, x, 0, 5-1);
  if (result == -1)
    cout<<"Not found";
  else
    cout<<"Element is found at index "<<result;
}

