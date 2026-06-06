int mySqrt(int x) {
    if (x == 0) return 0;   
    
    int left = 1, right = x;
    int ans = 0;

    while (left <= right) {
        long mid = left + (right - left) / 2;  

        if (mid * mid == x) {
            return (int)mid;  
        } else if (mid * mid < x) {
            ans = (int)mid;   
            left = mid + 1;   
        } else {
            right = mid - 1;  // search lower
        }
    }
    return ans;  // floor of sqrt(x)
}
