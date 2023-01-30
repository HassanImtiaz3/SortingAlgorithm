class Solution {
public:
    vector<vector<int>> threeSum(vector<int>& nums)
    {
        set<vector<int>>ans;
        vector<vector<int>>result;
        sort(nums.begin(), nums.end());
        

	for (int i = 0; i < nums.size(); i++)
	{
		int j = i + 1;
		int k = nums.size() - 1;

		while (j < k)
		{
			if (nums[i] + nums[j] + nums[k] == 0)
			{
				ans.insert( {nums[i],nums[j],nums[k]} );
				j++;
				k--;
			}
			else if (nums[i] + nums[j] + nums[k] < 0)
			{
				j++;
			}
			else
			{
				k--;
			}
           
		}

	}
    for(auto i : ans)
    {
        result.push_back(i);
    }
        return result;
    }
};
