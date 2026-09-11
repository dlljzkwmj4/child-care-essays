# 定义一个复数类complex重载运算符+使之能（定义一个复数类complex重载运算符）

> 更新时间：2026-09-10 (UTC+8)

您好,今天小编胡舒来为大家解答以上的问题。定义一个复数类complex重载运算符+使之能，定义一个复数类complex重载运算符相信很多小伙伴还不知道,现在让我们一起来看看吧！

1、#include using namespace std;class CComplex{ private: float real, image; public: CComplex() { } CComplex( float r, float img ) { real = r; image = img; } CComplex( CComplex another ) { real = another.real; image = another.image; } CComplex operator = (CComplex another ) { real = another.real; image = another.image; return this; } CComplex operator +( CComplexanother ) { return CComplex( real+ another.real, image + another.image ); }CComplex operator -( CComplexanother ) { return CComplex( real- another.real, image - another.image ); }CComplex operator ( CComplexanother ) { CComplex prod; //prod = this;prod.real = realanother.real - imageanother.image; prod.image = realanother.image + imageanother.real; return prod; //return CComplex( real+ another.real, image + another.image ); } CComplex operator /( CComplexanother ) { CComplex quot; float sq = another.realanother.real + another.imageanother.image; quot.real = (realanother.real + imageanother.image)/sq; quot.image = (imageanother.real - realanother.image)/sq; return quot; }};void main(){ CComplex c1( 2, 3 ), c2( 3, 3 ); CComplex c4, c5, c6, c7; c4 = c1 + c2; c5 = c1 - c2; c6 = c1c2; c7 = c1/c2;}。

本文就为大家分享到这里，希望小伙伴们会喜欢。

## 相关阅读

- [30岁有抗体是否会影响怀孕？还是只能试管婴儿？](https://github.com/uo8lrun64a/mommy-baby-notes/blob/main/20260910clmh/zqpzhpgavd.md)
- [长沙正规助孕机构怎么选择(附医院详情介绍)](https://github.com/uo8lrun64a/baby-care-journal/blob/main/20260910upmt/zvyjvolvvy.md)
- [咸宁三代试管双胞胎多少钱](https://github.com/y9qvvxks1i/mommy-baby-notes/blob/main/20260910mfuo/xduoushiki.md)
- [西安省妇幼试管三代包生男孩费用一览！](https://github.com/olvqsk2upx/child-care-essays/blob/main/20260910lvel/batyfzopvb.md)
- [上海单身女性赴泰国试管婴儿费用概览：新费用是多少？](https://github.com/agufpr6079/baby-care-journal/blob/main/20260910izwe/ntwsguyfog.md)
- [济南三代试管三代试管费用明细来了](https://github.com/qws8inv2p1/baby-care-journal/blob/main/20260910ybfx/lokxiuzrpl.md)
- [长沙试管婴儿医院排名哪家好？附带费用信息！](https://github.com/o8mgbpui8y/parenting-daily-tips/blob/main/20260910fsae/ngzaygnlza.md)
- [青岛试管婴儿收费标准 附费用参考](https://github.com/j4q35mmgu2/family-health-notes/blob/main/20260910hlxn/kssxgixnfe.md)
- [温州哪家医院可以做试管婴儿进行人工受孕？](https://github.com/l0mxvbb0j0/baby-care-journal/blob/main/20260910wdyp/nvpfmavenc.md)
- [没有结婚证可以去内蒙古包钢医院做三代试管生子吗？成功率高吗](https://github.com/b1xp80vbpv/family-health-notes/blob/main/20260910ddfw/anjdqiqkna.md)
- [做试管婴儿哪个医院技术好点？附机构名单](https://github.com/zntce2ojnh/pregnancy-care-hub/blob/main/20260910xuzh/tkpkzsqrqi.md)
- [三代试管生-女-孩的价格是多少？包生-女-孩费用10万够吗？](https://github.com/ovix8rnv9x/child-care-essays/blob/main/20260910zirb/pcmqnttzbv.md)

## 推荐站点

- [['https://www.sandwnot.com/114430629041.html', '2026辽宁三代试管婴儿助孕医院 费用 成功率的详细介绍']](https://www.sandwnot.com/114430629041.html)
- [['https://www.dyqlsu.com/20250418-396.html', '如何去做试管代孕,双子宫单宫颈可以做试管吗_单子宫双宫颈可以顺产吗！']](https://www.dyqlsu.com/20250418-396.html)
- [['https://www.sgdaiyun.com/226543182387.html', '杭州地区有哪些私立的机构可以做试管技术！杭州最有名的试管！']](https://www.sgdaiyun.com/226543182387.html)
- [['https://www.3899234.com/20250927-146.html', '生男孩子代怀&东莞试管婴儿医院排行榜你知道吗？']](https://www.3899234.com/20250927-146.html)
- [['https://www.cxit.com.cn/daiyunxinwen/14172.html', '长沙哪里代生孩子,长沙中信湘雅做供卵试管价格多少？长沙湘雅供卵中心电话']](https://www.cxit.com.cn/daiyunxinwen/14172.html)
- [['https://www.luruihang.com/2341.html', '吃黄体酮必须有撤退性出血吗']](https://www.luruihang.com/2341.html)
- [['https://www.jszgyh.com/228901837250.html', None]](https://www.jszgyh.com/228901837250.html)
- [['https://www.eduency.com/328651102213.html', '借卵怀孕机构:月经褐色血（月经血呈褐色是什么原因）']](https://www.eduency.com/328651102213.html)
- [['https://www.mimi567.com/219.html', '能做借卵试管:做试管婴儿前水果能吃吗（试管婴儿移植后吃什么水果好）']](https://www.mimi567.com/219.html)
- [['https://www.hg00fj88.com/2276.html', '试管代生网-卵巢早衰没有窦卵泡还有救么？别担心，有四种解救办法总有一种适合你']](https://www.hg00fj88.com/2276.html)
- [['https://www.monpun.com/6399007266871.html', '广州试管婴儿技术领先医院推荐']](https://www.monpun.com/6399007266871.html)
- [['https://www.zrbbavaq.cn/15468417231726.html', '做代生医院-代怀机构报价,试管激活费用是多少']](https://www.zrbbavaq.cn/15468417231726.html)
- [['https://www.cd-hssf.com/222610065206.html', '多囊卵巢会排卵吗？如何改善多囊卵巢综合征？']](https://www.cd-hssf.com/222610065206.html)
- [['https://www.sdxxy.cn/20250608-498.html', '济南哪有供卵中心的医院,济南托儿所日托价格看地区！附试管明细参考！']](https://www.sdxxy.cn/20250608-498.html)
- [['https://www.ewdboe.cn/510135462328.html', '湖北第三代代生医院排名：助孕省钱攻略2026版']](https://www.ewdboe.cn/510135462328.html)
- [['https://www.cecigou.cn/chuanchengguojidaiyun/20250928/15004.html', '孕中期胎儿8号染色体异常会对孩子造成哪些影响？']](https://www.cecigou.cn/chuanchengguojidaiyun/20250928/15004.html)

*本文整理自母婴健康资讯，仅供科普参考。*
