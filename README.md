# Weekly-problem
知乎编程学习群每周一题 Week 0

问题：如何挑选春节礼物

在北京工作的程序员小明今年过年要回老家，可是对于一个工作繁忙的程序员来说，如何给家里那么多亲戚朋友选择礼物确实是一个头疼的问题。你能不能帮帮他呢？

你的任务是帮他在北京机场的礼品店里买更可能多的礼物。
你有 X 元钱，而商店里可供选择的商品是由一个list/array表示的，其中每一项由那个商品的价格代表。（第i个项是第i个商品的价格）
每个商品在商店里只有一个，你的目标是买尽可能"多"的礼物。

你需要写一个function，里面的第一个输入是你所有的钱X， 第二个输入是商品的list：

	Python:
	#x=1 测试用
	#list=[1,2,3] 测试用
	def function(x,list):
		 #你的程序
		 return 商品个数
    	
    C:
   	int function(int x,int array[]){
    //你的程序
    return num;	
   	}
    	
   	Java:
    public static int method(int x,int[] array){
    //你的程序
    return num;
   	}
    	
如果什么都买不到，return 0.

例子：

	 *预算X：5     商品list：[3,8,1,2,3]
	  输出：2
 
 	 *预算X：3     商品list：[2,1,5]
	  输出：2
 
 	 *预算X：10     商品list：[1,1,1,1,2,5]
 	  输出：5
 
	 *预算X：10     商品list：[5,10,3,2]
  	  输出：3
 
	 *预算X：2    商品list：[3,8,10]
  	  输出：0
