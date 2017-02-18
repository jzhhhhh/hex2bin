# 项目简介
现在手头做的项目是成像声纳，产品前期配置中有一项是幅相校正，需要上位机获取声纳上传的数据，然后通过Matlab计算福相校正系数（txt格式文件），然后打开winhex软件，然后将上述txt文件内容（16进制）全部复制，然后在winhex里面新建一个文件，然后把txt内容粘贴进去，然后再保存，最后将文件通过软件下发到声纳中，除此之外还要删除winhex新建文件的默认内容，粘贴时选择编码方式等等步骤。因为产品最后需要量产，如此麻烦的操作步骤对配置人员的记忆要求更大，而且容易出错。
本项目就是针对这些问题而开发的一个易于操作的软件，使用本软件，操作人员只需打开本软件，然后在软件里选择txt文件的存储路径，然后点击“开始转换”按钮，软件就会自动生成所需要的dat文件，大大简化了幅相校正的操作步骤。

# 更新记录
- 2017.2.26 写测试程序，该程序只是实现基本测试，没有GUI。
- 2017.2.27 为程序加上GUI，并解决因Windows系统换行符导致的BUG。
