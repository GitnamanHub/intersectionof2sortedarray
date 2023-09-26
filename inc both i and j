#include <bits/stdc++.h> 
vector<int> findArrayIntersection(vector<int> &arr1, int n, vector<int> &arr2, int m)
{
	vector<int> ans;
	for(int i=0, j=0;i<n && j<m;)
	{
		if(arr1.at(i)==arr2.at(j))
		{
			ans.push_back(arr1.at(i));
			i++,j++;
		}

		else if(arr1.at(i)>arr2.at(j))
		{
			j++;
		}

		else if(arr1.at(i)<arr2.at(j))
		{
			i++;
		}
	}

	return ans;
}
