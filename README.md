# Python-Coding
### my pythin basic codings
def reverseInGroups(self, arr, N, K):
        # code here
        
        for i in range(0,N,K):
            if i>N-K:
                arr[i:N]=reversed(arr[i:N])
            else:
                arr[i:i+K]=reversed(arr[i:i+K])
                
        return arr
