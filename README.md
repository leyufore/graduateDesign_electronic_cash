# graduateDesign_electronic_cash
#A graduate design about electronic cash
本文旨在实现一个基于Android的电子现金管理系统。该基于Android的电子现金管理系统涉及银行、商户、用户三个角色，模拟了银行生成现金，用户提款，用户支付，商家存款的电子现金流通系统。该系统中涉及三个协议，分别为初始化协议、提款协议和支付存款协议。该系统中包含了五个功能，分别为1.初始化功能。2.开户功能。3.提款功能。4.支付存款功能。5.银行身份验证功能。
该方案中使用基于RSA的盲签名算法确保了电子现金具有不可追踪性，使用数字证书技术验证银行身份的正确，保障用户、商户的利益，同时利用银行在线的模式来保证用户支付给商家的电子现金是非重复支付的，防止用户欺诈。从实现层面验证电子现金协议方案的可行性。
该项目后台使用Strut2+Hibernate形式
该项目前台安卓端涉及技术：Volley，蓝牙
该项目数据库：Mysql
