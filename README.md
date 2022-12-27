# vpn
a quick way to create a vpn server in aws with CloudFormation

If you want to use the aws free tier resources, you should chose the Standard.VPN-t2.micro option for most regions,except for the regions listed below:
Asia Pacific (Hong Kong),Africa (Cape Town),Asia Pacific (Hyderabad),Asia Pacific (Jakarta),Europe (Zurich),Europe (Milan),Europe (Spain),Middle East (UAE),Middle East (Bahrain),Europe (Stockholm).
For those regions listed above, you should chose High.Speed.VPN-t3.micro option to use the aws free package.

For faster server option(not free),you can chose the Ultra.High.Speed.VPN-t3.medium option.


中文：
通过aws的CloudFormation快速创建vpn服务
注意：如果你想用aws的免费套餐，那么以下区域你要选择 High.Speed.VPN-t3.micro ：
香港，开普敦，德拉巴，雅加达，米兰，西班牙，斯德哥尔摩，苏黎世，巴林，阿联酋；
其他的区域（大部分区域）选择 Standard.VPN-t2.micro
如果想要更快的服务器（不在免费套餐内），你可以选择 Ultra.High.Speed.VPN-t3.medium
