# AutoUpdater

For Update automatically Freqtrade and his Strategy as soon as the updates are available
###### You can : 
###### update Freqtrade
###### update Strategy
###### update Pairlist
###### update Blacklist
###### update AutoUpdater	
###### You can show the difference between your old Blacklist and the newest
###### Send message to telegram for each update 
	

# Clone The Repository 

Clone The Repository to /ft_userdata/tools/

# Add script to crontab :                                                                                    
       typing "crontab -e" in terminal                                                                      
       write on the bottom of the file: */5 * * * * bash -lc [YOUR AUTOUPDATER PATH]/GRrHaG_AutoUpdater.sh  
             example : */5 * * * * bash -lc /home/pi/ft_userdata/tools/GRrHaG_AutoUpdater.sh               
       use ctrl+o for save crontab and ctrl+x for quit crontab                                              
       cd [YOUR AUTOUPDATER PATH]                                                                           
       chmod +x GRrHaG_AutoUpdater.sh 
       
# General Recommendations 

###### Place config_autoupdater.json in /ft_userdata/tools/
###### You can activate the updates by entering Y or deactivate them by leaving empty

## I recommend not to activate the update of the autoupdater but to come and check the updates by yourself and to see what changes in the code

# Donations   

BTC: 1KNscj7drzt2DUUTQXYorxzFmVJcuZ2AQq                                                                  
ETH (ERC20): 0x82edaf1338450976ef97112ca7b80ed2df2f5208                                                  
BEP20/BSC (USDT, ETH, BNB, ...) : 0x82edaf1338450976ef97112ca7b80ed2df2f5208                            
TRC20/TRON (USDT, TRON, ...): TGFwrnCn2tVU8RWESGhWbqKaCsLPUVZHbw                                        
                                                                                                            
# Referral Links                                                                                  
                                                                                                          
Binance: https://accounts.binance.com/fr/register?ref=44193596                                          
Kucoin: https://www.kucoin.com/ucenter/signup?rcode=2N8fcx3  
