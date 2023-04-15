# git_operator
git操作，github高级搜索
## Github高级搜索技巧	

`in:name <关键字>`
 仓库名称带关键字查询

`in:description <关键字>`
 仓库描述带关键字查询

`in:readme <关键字>`
 README文件带关键字查询



`stars(fork): >(=) <数字> <关键字>`
 star或fork数大于(或等于)指定数字的带关键字查询

`stars(fork): 10..20 <关键词>`
 star或fork数在10到20之间的带关键字查询



`size:>=5000 <关键词>`
 限定仓库大于等于5000K的带关键字查询

`pushed(created):>2019-11-15 <关键字>`
 更新 或 创建 日期在2019年11月16日之后的带关键字查询

`license:apache-2.0 <关键字>`
 LICENSE为apache-2.0的带关键字查询

`language:java <关键词>`
 仓库语言为Java的带关键字查询



`user:<用户名>`
 查询某个用户的项目

`org:<组织名>`
 查询某个组织的项目

***以上查询条件可组合使用，空格隔开**

```sh
# 示例1：搜索仓库名包含javascript，并且stars数大于1000的项目
in:name javascript stars:>1000

# 示例2：搜索描述中包含"小程序"，并且fork大于100，并且最近更新时间在2019-11-15之后的，并且使用开发语言为vue的项目
in:description 小程序 fork:>100 pushed:>2019-11-15 language:vue
```

特殊的查找资源小技巧-常用前缀后缀 
• 找百科大全 awesome xxx <br>
• 找例子 xxx sample<br>
• 找空项目架子 xxx starter / xxx boilerplate <br>
• 找教程  xxx tutorial<br>

***或使用高级搜索页搜索：**

<https://github.com/search/advanced>
# Good-Search_Github
使用Github的高级搜索

# 用法

| 搜索条件 | 使用方法 | 备注 |
| :-- | :--: | :--: |
| location: | location:china | 匹配填写的地址在china的开发者 |
| language: | language:python | 匹配开发语言为python的项目 |
| followers: | followers:>=1000 | 匹配拥有超过1000名关注着的项目 |
| in:name | in:name Wangrongsheng | 匹配用户名为Wangrongsheng的开发者 |
| in:descripton | in:descripton python | 匹配仓库描述里面有python的项目 |
| in:readme | in:readme python | 匹配README描述中有python的项目 |
| stars: | stars:>=500 | 匹配收藏数量超过500的项目 |
| forks: | forks:>=500；forks: 10..20 | 匹配分支数量超过500的项目；匹配分支数量为10-20的项目 |
| size: | size:>=5000 | 匹配仓库大于5000KB的仓库 |
| created: | created:>2019-01-01 | 匹配2019年以后创建的仓库 |
| pushed: | pushed:>2019-01-01 | 匹配仓库最近一次提交在2019年以后的仓库 |
| license: | license:apache-2.0 | 匹配使用 apache-2.0 协议的仓库 |
| user: | user:google | 匹配用户google 上传的仓库 |
| org: | org:spring-cloud | 匹配列出org的spring-cloud仓库 |
| Awesome + 关键字 | 神器关键字 | 帮助找到优秀的工具列表 |

除此之外，还可以**组合使用**哦

