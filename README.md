# Omnibrowser--issue

<br><br><br><br><br><br>

## 网站问题@肖亮
### 1.收索框模糊匹配 搜索文章名全称不行，搜几个单词可以。
### 2.login successful的提示还要手动x掉，可以换成自动隐藏。
### 3.网站登录登出功能，同时在线人数限制。
### 4.把resetpassword功能移到首页和搜索结果页

<br><br><br><br><br><br>

## 数据问题@张天然
### 1.No_140_1 No_162_1 No_162_2 No_162_6 No_162_7 No_186_1 No_271_1 No_329_2 No_340_1 No_340_2 No_73_1 的defaultGeneInput字段没有

<br><br><br><br><br><br>

## API问题@李玥
### 1.http://47.92.36.58:9099/market/gene_hint 和 http://47.92.36.58:9099/market/obs/<str:dataset_ID>
#### No_337_1  No_342_1   No_54_3   No_54_4  No_54_5  这5个数据集请求没有返回
### 2.http://47.92.36.58:9099/market/paga
#### "No_140_1","No_162_1","No_162_2","No_162_6","No_162_7","No_172_1","No_184_1","No_186_1","No_271_1","No_279_1","No_329_2","No_340_1","No_340_2","No_38_1","No_73_1" 这些数据集请求没有返回值
### 3.http://47.92.36.58:9099/market/query_gene_expression_all_cells
#### "use_sum":"TRUE"  没有问题  "use_sum":"FALSE" 有问题的数据集 :No_136_5 No_156_1 No_167_1 No_221_1  No_241_1  No_290_1 No_326_1 No_38_1 （其中No_136_5  "expression_vector"里面有”NaN”）

