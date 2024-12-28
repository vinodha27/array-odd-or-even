# array-odd-or-even
 int[] a={1,2,3,4,5,6,7};
        int i;
        for(i=0;i<=a.length-1;i++)
        {
            if(a[i]%2==0)
            {
                System.out.println(a[i]+"is even ");
            }
            if(a[i]%2!=0)
            {
                System.out.println(a[i]+"is odd");
            }
        }
