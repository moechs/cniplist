# 中国IP列表 China IP list

> 本仓库仅做备份，不定时同步更新。

| IP列表 | 说明 |
| ----------- | ----------- |
| Aggregated_ChinaAllNetwork_IPv4.txt | 中国所有IPv4列表 |
| Aggregated_ChinaAllNetwork_IPv6.txt | 中国所有IPv6列表 |
| Aggregated_ChinaMobile_IPv4.txt | 移动IPv4列表 |
| Aggregated_ChinaMobile_IPv6.txt | 移动IPv6列表 |
| Aggregated_ChinaTelecom_IPv4.txt | 电信IPv4列表 |
| Aggregated_ChinaTelecom_IPv6.txt | 电信IPv6列表 |
| Aggregated_ChinaUnicom_IPv4.txt | 联通IPv4列表 |
| Aggregated_ChinaUnicom_IPv6.txt | 联通IPv6列表 |
| Aggregated_ChinaEducation_IPv4.txt | 教育网IPv4列表 |
| Aggregated_ChinaEducation_IPv6.txt | 教育网IPv6列表 |
| Aggregated_ChinaSciences_IPv4.txt | 科技网IPv4列表 |
| Aggregated_ChinaSciences_IPv6.txt | 科技网IPv6列表 |

#### ☆ 数据引用说明 ☆

* 商业转载请联系作者获得授权，非商业转载请注明出处。
* For commercial use, please contact the author for authorization. For non-commercial use, please indicate the source.
* 协议(License)：署名-非商业性使用-相同方式共享 4.0 国际 (CC BY-NC-SA 4.0)
* 作者(Author)：小林白渃
* 链接(URL)：[https://blog.bairuo.net/2024/03/09/完全基于bgp的五大国内骨干网分流ip-list/](https://blog.bairuo.net/2024/03/09/%e5%ae%8c%e5%85%a8%e5%9f%ba%e4%ba%8ebgp%e7%9a%84%e4%ba%94%e5%a4%a7%e5%9b%bd%e5%86%85%e9%aa%a8%e5%b9%b2%e7%bd%91%e5%88%86%e6%b5%81ip-list/)
* 来源(Source)：小林家的白渃

> 基于BGP路由表生成IP列表，并使用了ASN作为IP划分的依据，较使用WHOIS生成的IP列表具有更佳的有效性和实时性，因为基于BGP生成，产生的IP是一定可以通过互联网路由到的，使用WHOIS会包含一些没有被广播的前缀，这种IP就算添加至分流列表也没有实际意义，同时基于ASN的判断方法确保了导出的IP列表一定是中国互联网的IP，使用WHOIS导出可能会包含IP的inet或route记录属于中国，实际上在国外广播的IP（比如一车BGPlayer的IP）
