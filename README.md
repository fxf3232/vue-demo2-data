//数据主页
http://localhost:3000/

//获取所有用户信息
http://localhost:3000/users

//获取所有用户ID为1的信息
http://localhost:3000/users/1

//获取公司的所有信息
http://localhost:3000/companies

//获取ID为1的公司的信息
http://localhost:3000/companies/1

//获取所有公司ID为3的用户
http://localhost:3000/companies/3/users

//根据公司名称获取信息
http://localhost:3000/companies?name=baidu

//根据多个名称获取公司信息
http://localhost:3000/companies?name=baidu&name=apple

//获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2       //_page:当前的页数 , _limit:限制只展示几条

//获取的数据进行升序排序
http://localhost:3000/companies?_sort=name&_order=asc    //asc:升序，desc:降序

//获取用户年龄为30以上的
http://localhost:3000/users?age_gte=30

//获取用户年龄为30到40之间的
http://localhost:3000/users?age_gte=30&age_lte=40

//根据搜索用户信息，获取相关数据
http://localhost:3000/users?q=z   //搜索条件为字符中带有 "z"

