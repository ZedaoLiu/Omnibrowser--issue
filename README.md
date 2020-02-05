# Omnibrowser--issue

<br><br><br><br><br><br>

## 网站问题@肖亮

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
### 4.http://47.92.36.58:9099/market/paga返回数据中的node_name 和 http://47.92.36.58:9099/market/obs/返回数据中的clusterName对应不上 No_4_1

### 发布版数据库里含有一个No_i1_1,目前未发现对功能的影响，文杰的代码里知道有这个数据集存在，可以问文杰是什么原因。
