# python-AI-11-
python+AI笔记(11)
# 一阶-六章-数据容器入门
#数据容器是一种可以容纳多份数据的类型，容纳的类型可以是任何类型
#根据是否支持重复元素，是否可以修改，是否有序来进一步将数据容器划分为5类
#列表、元组、字符串、集合、字典

# 一阶-六章-列表的定义语法
#列表中的每一个数据称之为元素，列表以[]作为标识
#定义一个列表list
my_list=["balabala","calacala","python"]  #列表的定义
print(my_list)
print(typ0e(my_list))
my_list=["bala",666,True]  #列表的元素类型是不受限的

#定义一个嵌套列表
my_list=[[1,2,3],[4,5,6]]
print(my_list)
print(type(my_list))

# 一阶-六章-列表的下标索引
#列表的下标索引也是从0开始
my_list=["Tom","Lily","Rose"]
print(my_list[0])
print(my_list[1])
print(my_list[2])
#结果输出Tom，Lily，Rose

#通过下标索引倒序取出数据
print(my_list[-1])
print(my_list[-2])
print(my_list[-3])
#结果输出相反

#取出嵌套列表的元素
my_list=[[1,2,3],[4,5,6]]
my_list[1][1]  #输出5
