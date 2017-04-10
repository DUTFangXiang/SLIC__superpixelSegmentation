
# SLIC__superpixelSegmentation
超像素分割原算法在windows下mex有error，这是对该算法的修正版本
### 说明
　　超像素分割在计算机视觉领域有很大的应用，其中SLIC算法应用最热门，速度快并且效果非常好，算法是Radhakrishna Achanta等人提出，先后发表下面两篇文章：
  
　　【1】Radhakrishna Achanta, Appu Shaji, Kevin Smith, Aurelien Lucchi, Pascal Fua, and Sabine Süsstrunk, 
    SLIC Superpixels Compared to State-of-the-art Superpixel Methods, IEEE Transactions on Pattern Analysis 
    and Machine Intelligence, vol. 34, num. 11, p. 2274 - 2282, May 2012.
    
    【2】Radhakrishna Achanta, Appu Shaji, Kevin Smith, Aurelien Lucchi, Pascal Fua, and Sabine Süsstrunk, 
    SLIC Superpixels, EPFL Technical Report no. 149300, June 2010.
### 修改：
　　但是源程序slicmex.c在windows系统下编译是有错误的，主要提示如下：slicmex.c(387) : error C2275: “mwSize”:将此类型用作表达式非法。
  
　　这是一个很典型的纯c程序的错误。详细修改说明，请翻阅本人博客：

　　http://blog.csdn.net/fx677588/article/details/53694406
