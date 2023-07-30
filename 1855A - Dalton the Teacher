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

    ll diff = 0;

    for (int i = 0; i < n; i++)
        if (arr[i] == i + 1)
            diff++;

    if (diff & 1)
        cout << diff / 2 + 1 << nline;
    else
        cout << diff / 2 << nline;
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
