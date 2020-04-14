# generatorSqlmapCustom
java逆向工程--sql文件映射出Pojo和Mapper
1. 导入逆向工程到eclipse中
  采用import->General->Existing Projects into Workspace方式导入,
  选择该包的保存路径.
2. 修改配置文件
  在generatorConfig.xml中配置Mapper生成的详细信息, 
    注意修改以下几点:
      1.	修改要生成的数据库表
      2.	pojo文件所在包路径
      3.	Mapper所在的包路径
3. 生成逆向工程代码
  执行工程main主函数,刷新工程，发现代码生成.
