# data_structure_c

关于树的插入需要注意, 根节点作为不作为参数传入, 如果作为参数传入, 那么必须要返回一个节点指针或者将指向指针的指针作为参数传入.
如果不作为参数传入, 则要在函数前单独建立一个根节点, 对此节点进行操作.
实际上我认为清除一个树同样需要做这种操作, 否则空间会被一直占用, 即使返回的是一棵空树, 但是空间却没有释放.
