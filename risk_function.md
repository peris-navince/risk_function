# C语言风险函数
strcpy  
strtok  
strcat  
sprintf  
sscanf  
strncpy  
system  
fork  

# Tenda风险函数
websgetvar()  
或以websget开头的函数；  
websUrlHandlerDefine

# TOTOLINK风险函数
websgetvar()  
CsteSystem()  
Uci_Set_Str()

# NETGEAR风险函数
R6250:
sub_16B04()(This function receives data from network traffic, similar to websgetvar(), and is a different function in different firmwares.)
acosNvramConfig_get()
acosNvramCongif_set()
