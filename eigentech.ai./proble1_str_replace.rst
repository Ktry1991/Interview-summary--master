.. code:: ipython3

    # %% 1
    # Using 2 decimal system replace binary tree 
    def replace_str(target_str):
        target_str = target_str.replace('b','X')
    
        st = target_str.split('a')
        count_a = len(st)-1
        all_s = []
        for i in range(count_a):
            s = ''
            for j in range(2**(count_a):    #用二进制中的0,1记录替换后字符串中的C,B
                bin_str = bin(i).replace('ob','')  
                if (1<<j) & i:  
                    s+='B'+st[j+1]
                else:
                    s+='C'+st[j+1]
            print(s)
            all_s.append(s)
            
    if __name__ == "__main__":
        test = 'aghaswabbeeba'
        replace_str(test)


.. parsed-literal::

    ['', 'gh', 'sw', 'XXeeX', '']
    16
    CghCswCXXeeXC
    BghCswCXXeeXC
    CghBswCXXeeXC
    BghBswCXXeeXC
    CghCswBXXeeXC
    BghCswBXXeeXC
    CghBswBXXeeXC
    BghBswBXXeeXC
    CghCswCXXeeXB
    BghCswCXXeeXB
    CghBswCXXeeXB
    BghBswCXXeeXB
    CghCswBXXeeXB
    BghCswBXXeeXB
    CghBswBXXeeXB
    BghBswBXXeeXB

