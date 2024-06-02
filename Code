using namespace std;

class Solution {
public:
    void reverseString(vector<char>& s) {
        char c;
        for(int i=0, j=s.size()-1 ; i<s.size()/2; i++, j--)
        {
            c =s[i];
            s[i]=s[j];
            s[j]=c; 
        }

        cout << "[";
        for(int i=0;i<s.size();i++)
        {
            cout <<"\"" << s[i] << "\"";
            if(i!=s.size()-1)
                cout <<",";
        }
        cout << "]"<< endl;
    }
};
