tasking：
	1. 统计每个item有多少
		输入：barcodes：[String]
		输出：cartItem: [{itemCode:String, quantity: int}]
	2. 完善item的信息
		输入：cartItem: [{itemCode:String, quantity: int}]
		输出：cartItem: [{itemCode:String, itemName: String, quantity: int, unitPrice: int}]
	3. 计算全部商品的总价
		输入：cartItem: [{itemCode:String, itemName: String, quantity: int, unitPrice: int}]
		输出：totalPrice: int
	4. 格式化我们的数据
		输入：cartItem: [{itemCode:String, itemName: String, quantity: int, unitPrice: int}]
			  totalPrice: int
		输出: receipt: String (单个商品的总价在这里用单价*数量，我感觉不用分多一步出来，在这直接乘就好了)
	5. 输出数据
		输入: String
		输出：打印到了控制台上

		
		统计每个item有多少
	P	3min
	D	20min
	C	查了很久js统计数量的方法和js容器
	A	要多练习js编程
	
		完善item的信息
	P	3min
	D	25min
	C	同样查了很久的js方法
	A	要多练习js编程
	
	
		计算全部商品的总价
	P	3min
	D	10min
	C	之前查的方法在这也能用，就快了一点
	A	要多练习js编程

		格式化我们的数据
	P	7min
	D	5min
	C	格式化比较简单
	A	照着需求来拼接
	
		输出数据
	P	4min
	D	6min
	C	这里超了时间是因为要照着错误来更改格式,实际原因还是不太熟JS
	A	要多练习js编程