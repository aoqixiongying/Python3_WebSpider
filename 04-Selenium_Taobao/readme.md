##声明：
	*本次爬取参考"崔庆才-Python3网络爬虫开发实践"第七章7.4节.*

##使用Selenium爬取淘宝商品数据简介：
	*使用Selenium模拟浏览器操作，抓取淘宝商品数据，并将结果存储至MongoDB.
	*商品信息包括：商品图片、名称、价格、购买人数、店铺名称和店铺所在地信息.
	*需要事先安装Chorme浏览器和对应版本的ChromeDriver；另外需要正确安装Selenium库.
	*采取Selenium爬取的原因：不需要考虑Ajax接口及其参数的规律，只要在浏览器中可以看到的，都可以爬取.

##待优化的地方：
	*商品信息没有考虑去重，后期做优化
	*商品数据待做数据可视化分析，原因：购买者需要看到真实的评价情况或者好评度等等，若做条形图或饼状图将会更加直观，节省时间，提高效率.
	*数据库存储部分

##存在的问题：
	*未解决爬取过程的用户登录以及验证码问题，后期定会解决，时间问题.
	*爬取速度问题