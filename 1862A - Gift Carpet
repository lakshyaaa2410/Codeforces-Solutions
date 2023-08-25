#include <bits/stdc++.h>
#define ll long long int
#define nline '\n'
using namespace std;

void solve()
{
    ll n, m;
    cin >> n >> m;

    char s[n][m];

    for (int i = 0; i < n; i++)
        for (int j = 0; j < m; j++)
            cin >> s[i][j];

    string name = "vika";
    ll ind = 0, count = 0;
    
    for (int i = 0; i < m; i++)
    {
        for (int j = 0; j < n; j++)
        {
            char curr = s[j][i];
            if (curr == name[ind])
            {
                ind++;
                count++;
                break;
            }
        }

        if (count == 4)
            break;
    }

    if (count == 4)
        cout << "Yes\n";
    else
        cout << "No\n";
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
