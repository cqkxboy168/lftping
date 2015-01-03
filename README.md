LFT use ICMP time exceeded packets (TTL expired in transit) to measuring latency. PING use ICMP Echo Request packets to measure latency. LFTPING can get echo hop latency by PING and LFT methods at the same time. Like as follow,

{"tool":"lft","ip":"112.1.32.1","protocol":"icmp","trace":[
{"type":"icmp no reply from target","note":"Try advanced options to see packets"}
]}
{"tool":"lft","ip":"112.2.32.1","protocol":"icmp","trace":[
{"seq":1,"asn":4837,"net":"APNIC-27/UNICOM-CQ","ip":"27.10.56.1","lfttime":"65.91/30.99/30.93 ms","pingtime":"31.297 ms"}
,{"seq":2,"asn":4837,"net":"APNIC7/UNICOM-CQ","ip":"221.5.246.169","lfttime":"35.76/33.89/31.93 ms","pingtime":"31.399 ms"}
,{"seq":3,"asn":4837,"net":"APNIC7/UNICOM-CQ","ip":"221.5.239.37","lfttime":"70.99/64.12/64.37 ms","pingtime":"67.958 ms"}
,{"seq":4,"asn":4837,"net":"APNIC5/CNCGROUP","ip":"219.158.99.213","lfttime":"58.30/60.32/60.58 ms","pingtime":"60.741 ms"}
,{"seq":5,"asn":4837,"net":"APNIC5/CNCGROUP","ip":"219.158.100.201","lfttime":"97.44/97.23/96.30 ms","pingtime":"98.726 ms"}
,{"seq":6,"asn":4837,"net":"APNIC5/ChinaUnicom-BACKBONE","ip":"219.158.4.78","lfttime":"86.44/85.54/84.53 ms","pingtime":"86.052 ms"}
,{"seq":7,"asn":4837,"net":"APNIC5/CNCGROUP-BACKBONE","ip":"219.158.34.242","lfttime":"84.18/86.13/96.11 ms","pingtime":" ms"}
,{"seq":8,"asn":9808,"net":"APNIC7/CMNET","ip":"221.176.17.33","lfttime":"99.55/121.01 ms"asn":9808,"net":"APNIC7/CMNET","ip":"221.176.17.161","lfttime":"84.92 ms","pingtime":"86.746 ms"}
,{"seq":9,"asn":9808,"net":"APNIC7/CMNET","ip":"221.183.10.125","lfttime":"93.31 ms"asn":9808,"net":"APNIC7/CMNET","ip":"221.183.10.81","lfttime":"93.81 ms"asn":9808,"net":"APNIC7/CMNET","ip":"221.183.10.121","lfttime":"112.74 ms","pingtime":"104.893 ms"}
,{"seq":10,"asn":9808,"net":"APNIC7/CMNET","ip":"221.183.12.10","lfttime":"92.01/96.65 ms","pingtime":" ms"}
,{"seq":11,"asn":56046,"net":"APNIC7/CMNET","ip":"221.181.243.2","lfttime":"112.93 ms","pingtime":"105.957 ms"}
,{"seq":12,"asn":56046,"net":"APNIC4/CMNET-jiangsu","ip":"218.206.97.114","lfttime":"95.83 ms","pingtime":"94.698 ms"}
,{"seq":13,"asn":56046,"net":"APNIC-112/CMNET","ip":"112.2.32.1","lfttime":"90.61 ms","pingtime":"91.809 ms"}
]}
