#include <bits/stdc++.h>
#define ll long long int
#define nline '\n'
using namespace std;

void solve()
{
    ll n;
    cin >> n;

    ll evenSum = 0, oddSum = 0;
    for (int i = 0; i < n; i++)
    {
        ll t;
        cin >> t;

        if (t & 1)
            oddSum += t;
        else
            evenSum += t;
    }   

    if (evenSum > oddSum)
        cout << "YES\n";
    else
        cout << "NO\n";
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
