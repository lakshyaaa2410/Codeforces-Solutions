#include <bits/stdc++.h>
#define ll long long int
#define nline '\n'
using namespace std;

void solve()
{
    ll n;
    cin >> n;

    string s;
    cin >> s;

    ll first = 0, last = 0;

    for (int i = 0; i < n; i++)
    {
        if (s[i] == 'B') 
        {
            first = i;
            break;
        }
    }

    for (int i = n - 1; i >= 0; i--)
    {
        if (s[i] == 'B')
        {
            last = i;
            break;
        }
    }

    cout << last - first + 1 << nline;
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
