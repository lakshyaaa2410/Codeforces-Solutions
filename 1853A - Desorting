#include <bits/stdc++.h>
#define ll long long int
#define nline '\n'
using namespace std;

void solve()
{
    ll n;
    cin >> n;

    vector<ll> arr(n);

    for (int i = 0; i < n; i++)
        cin >> arr[i];

    ll minDiff = INT_MAX;

    for (int i = 0; i < n - 1; i++)
    {
        if (arr[i] > arr[i + 1])
        {
            cout << 0 << nline;
            return;
        }
        else
        {
            minDiff = min(minDiff, (arr[i + 1] - arr[i]));
        }
    }

    cout << minDiff / 2 + 1 << nline;
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
