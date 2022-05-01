class Solution {
public:
    int recur(long long n,vector<int> dp)
    {
        if(n==0)return 1;
        if(n==1)return 1;
	
        if(dp[n]!=-1)return dp[n];
	
        int jump1=recur(n-1,dp);
        int jump2=recur(n-2,dp);
	
        return jump1+jump2;
    }
    int climbStairs(int n) {
        vector<int> dp(n+1,-1);
        return recur(n,dp);
    }
};
