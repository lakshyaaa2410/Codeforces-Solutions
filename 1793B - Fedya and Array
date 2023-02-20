#include <bits/stdc++.h>
#define ll long long int
#define nline '\n'
using namespace std;

void solve()
{
    ll x, y;
    cin >> x >> y;

    ll minPos = 2 * (abs(x - y));
    cout << minPos << nline;

    ll curr = x;

    while (curr != y) {
        cout << curr << " ";
        curr--;
    }

    while (curr != x) {
        cout << curr << " ";
        curr++;
    }

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
