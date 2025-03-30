class Solution {
public:
    vector<int> topKFrequent(vector<int>&a, int k) {
  int n=a.size();
map<int , int > m;

  for(int i=0 ; i< n ; i++)
{
m[a[i]]++;
}   

vector<pair<int , int>> arr(m.begin(),m.end());

sort(arr.begin(), arr.end(), [](const pair<int, int>& p1, const pair<int, int>& p2) {
            return p1.second > p2.second; 
        });
vector<int>ans;
int i=0;
while(k--){
     ans.push_back(arr[i].first);
i++;
}

return ans;
    }
};
