#include <bits/stdc++.h>
#define ll long long int
#define nline '\n'
using namespace std;

void solve()
{
    ll n;
    cin >> n;

    ll currWinner = 0, pos = 0;

    for (int i = 0; i < n; i++)
    {
        ll m, q;
        cin >> m >> q;

        if (m <= 10)
        {
            if (q > currWinner)
            {
                currWinner = q;
                pos = i + 1;
            }
        }
    }

    cout << pos << nline;
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
