#include <bits/stdc++.h>
#define ll long long int
#define nline '\n'
using namespace std;

void solve()
{
    ll n;
    cin >> n;

    ll arr[n];
    for (int i = 0; i < n; i++)
        cin >> arr[i];

    vector<ll> ans;
    ans.push_back(arr[0]);

    for (int i = 1; i < n; i++)
    {
        if (arr[i] >= arr[i - 1])
            ans.push_back(arr[i]);
        else
        {
            ans.push_back(1);
            ans.push_back(arr[i]);
        }
    }

    cout << ans.size() << nline;
    for (auto itr : ans)
        cout << itr << " ";
    cout << nline;
}

int main()
{
    ios_base::sync_with_stdio(false);
    cin.tie(NULL);
    ll T = 1;
    cin >> T;
    while (T--) 
    {
        solve();
    }
}
