# collectDataFrom_Excel
Reading data from Excel is easy task, when data formatting in a certain structure. But in reality, there are much more tables contain many different small tables in one sheet. This project is about to solve the problem.
从Excel中读取数据本身并不难，特别是Excel中的数据已经按照一定的结构排列好后。但现实是，我们经常需要处理包含有结构各异表格的Sheet。例如包含有“利润表”、“现金流表”、“资产负债表”等多个二维表格的财务报表，如果需要自动地从上百份类似文件中读取数据，并导出到一个数据库中，就没那么容易了。。
本项目尝试使用Python语言，利用爬虫方法，编制一个自动处理Excel中二维表格的算法。
