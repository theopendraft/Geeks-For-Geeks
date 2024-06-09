class Solution {
  public:
    void zigZag(int n, vector<int> &arr) {
        int i =0;
        while(i<(n-1)){
            
             if(i%2==0){
                if(arr[i]<arr[i+1]){
                    i++;
                }
                else{
                    swap(arr[i], arr[i+1]);
                    i++;
                }
            }
            else if(i%2!=0){
                if(arr[i] > arr[i+1]){
                    i++;
                }
                else{
                    swap(arr[i], arr[i+1]);
                    i++;
                }
            }
           
        }
         return;
    }
    
};
