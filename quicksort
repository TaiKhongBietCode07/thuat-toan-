// phan hoach lumoto
int parition(int a[], int l, int r) {
   int pivot = a[r]; i = l - 1;
   for (int j = 0; j < r; ++j) {
      if(a[j] < pivot) {
        ++i;
        swap(a[i], a[j];)
        }
      }
    ++i;
    swap(a[i], a[r]);
    return i;
    }
void quicksort(int a[], int l ,int r) {
  if(l >= r) return;
  int q = partition(a, l, r);
  quicksort(a, l , q - 1);
  quicksort(a, q + 1, r);
  }
