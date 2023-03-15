# guard  
# 配置文件 /etc/wireguard/wg0.conf  
# # 启动Wireguard
wg-quick up wg0  
 
#关闭WIreguard
wg-quick down wg0  
 
# 查看Wireguard状态  
wg

# 设置开机启动
systemctl enable wg-quick@wg0  

# 取消开机启动
systemctl disable wg-quick@wg0  

# 绕过大陆
https://github.com/lmc999/auto-add-routes  
