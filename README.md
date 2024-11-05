NodePay Multi Account 100% Uptime FREE Python Bot [v2] Bot
This Python Bot script manages WebSocket connections through specified HTTP proxies, Unlimited Proxies and multiple Nodepay Accounts handling authentication and maintaining persistent connections with a server. The script also includes functionality to periodically send ping messages to keep the connection alive forever. If you can run your pc 24/7 then you dont need a Vps or proxy server lol.

Features
    Connects to a WebSocket server using HTTP proxies.
    Handles Multiple Nodepay User IDs at once !! Multiple Proxies (1 Proxy ~60 $NODEPAY)
    Per Proxy ~1400 ** $NODEPAY per day** Unlimited proxies Make Unlimited Money !
    Handles All kinds of Error such a Dead proxy/ SSL: WRONG_VERSION_NUMBER / sent 1011 (internal error) keepalive ping timeout; no close frame received / 500 Internal Server Error / sent 1011 (internal error) keepalive.
    Automatically removes the dead proxy from the File!!
    #Get NP_TOKEN

    Open the link and log in https://app.nodepay.ai/dashboard
    Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
    Write const token =localStorage.getItem('np_token')
    copy(token);
    in the console
    Paste token into data.txt 

Requirements
    Invitation link Nodepay Accounts ( https://app.nodepay.ai/register?ref=TX6SxUqjX0zlDtW )
    Python (install Python By - https://www.python.org/downloads/ [windows/mac]) or Ubuntu Server [sudo apt install python3]
    VPS Server ! You can get Via AWS free Tier or Google Free tier or Gitpod or any online for just ~ 2-5$ per month
    Proxy Server - you can buy DataCenter Proxies to Earn $NODEPAY Some Free Cheap proxies (Best proxy providers is webshare)
    Get NP_token andcUser ID from Nodepay Dashboard


SETPS TO RUN THE CODE -
    Before running the script, ensure you have Python installed on your machine. Then, install the necessary Python packages using:

    git clone https://github.com/bangboongdev/nodepay.git
    cd nodepay
    pip install -r requirements.txt
    Replace NP TOken list in correct formate in node.py File Line 9.
    By default 100 proxies will be taken randomly if you wana change then change here active_proxies = [proxy for proxy in all_proxies[:100] if is_valid_proxy(proxy)] line 169. Here 100 means 100 proxy will be used at once.
    Dont Forget to add multiple proxies in the proxy.txt file you can add 1000+ proxy !! Formate # HTTP://username:pass@ip:port.
    You can get Multiple Proxy Ip address from Proxies.fo Website !! [use multiple IP ! 1 IP == ~1400 $NODEPAY per Day .
    To Run Script python3 node.py - Proxy one
    To Run multiple User ID just copy paste the node.py file code and create new python file and repeat the process !!.
Note - 1 ip == 1000-1400 $Nodepay Per Day.

