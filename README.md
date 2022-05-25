classSolution:
    def isPowerOfThree(self,n):
        if n==1:
            return True
        if n<1:
            return False
        return self.isPowerOfThree(n//3) if n%3==0 else False
