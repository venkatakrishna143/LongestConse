# LongestConse

int maxConsecutiveOnes(int x)
{

int ans = 0;
while(x!=0){
x = x&(x>>1);
ans++;
}
return ans;

}
