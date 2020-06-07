# integer-array
    Public static int minimizebias(list<integers>ratings). 
    {
     int sum=0;
     int Len=ratings.size();
     Collections.sort(ratings);
     for (inti=0;i<=len-1;i+=2)
     {
       int diff=ratings.get(I+1)-ratings.get(i
)      Sum+=diff;
       }
       Return sum;
       }
       }
