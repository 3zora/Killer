@echo off
chcp 65001
title Killer Tool By 3zora
color f0

:menu
cls                                                                    
echo          [30m_ _,---._                                              
echo       [30m,-','       `-.___
echo     [30m ^/-;'               `._
echo     [30m^/^\ ^/          ._   _,'[30mo [30m^\            
echo    [30m( ^/^\       _,--'^\,','"`. )                       
echo     [30m^|^\      ,'[30mo     [30m^\'    ^/ ^/^\              
echo     [30m^|      ^\        ^/   ,--'""`-.
echo     [30m:       ^\_    _ ^/ ,-'         `-._               
echo      [30m^\        `--'  ^/                ) 
echo       [30m`.  ^\`._    ,'     ________,','
echo         [30m.--`     ,'  ,--` __^\___,;'                              
echo          [30m^\`.,-- ,' ,`_)--'  ^/`.,'
echo           [30m^\( ;  ^| ^| )      (`- ^/
echo             [30m`--'^| ^|)       ^|- ^/
echo               [30m^| ^| ^|        ^| ^|
echo               [30m^| ^| ^|[30m,.,-.   ^| ^|_
echo               [30m^| `. ^[30m/ [30m^/   )---`  )
echo              [30m_^|  ^[30m/    ,',   ,-'
echo             [30m,'^|_[30m(    [30m^/-^<._,' ^|--,
echo             [30m^|    [30m`[30m--'---.     ^\ ^/ ^\
echo             [30m^|          ^/ ^\    ^/^\  ^\
echo           [30m,-^---._     ^|  ^\  ^/  ^\  ^\
echo        [30m,-'        ^\----'   ^\ ^/    ^\--`.
echo      [30m ^/            ^\              ^\   ^\
echo [96m                ╔══════════════════════════╗
echo                 ║   1  [96mPort scanner        ║    
echo [96m                ║   [96m2  [96mIp lookup           [96m║        
echo [96m                ║   [96m3  [96mDos ip              [96m║               
echo [96m                ║   [96m4  [96mUser look           [96m║    
echo [96m                ╚══════════════════════════╝

set /p choice=(!) 

if "%choice%"=="1" (
    call :scanIPRange
    goto menu
) else if "%choice%"=="2" (
    call :ipGeoLookup
) else if "%choice%"=="3" (
    call :dos_ip
    goto menu
) else if "%choice%"=="4" (
    call :username_lookup
    goto menu

goto menu

:username_lookup
set /p username=Enter the username you want to lookup: 
 
echo [94m╔═══════════════════════════════════════════════════════════════════════════════════════════════════╗
echo [94m║ .dP"Y8 888888    db    88""Yb  dP""b8 88  88     88""Yb 888888 .dP"Y8 88   88 88     888888 .dP"Y8║
echo [94m║ `Ybo." 88__     dPYb   88__dP dP   `" 88  88     88__dP 88__   `Ybo." 88   88 88       88   `Ybo."║
echo [94m║ o.`Y8b 88""    dP__Yb  88"Yb  Yb      888888     88"Yb  88""   o.`Y8b Y8   8P 88  .o   88   o.`Y8b║
echo [94m║ 8bodP' 888888 dP""""Yb 88  Yb  YboodP 88  88     88  Yb 888888 8bodP' `YbodP' 88ood8   88   8bodP'║
echo [94m╚═══════════════════════════════════════════════════════════════════════════════════════════════════╝ 
echo.
echo                [37m╔════════════════════════════════════════════════════════════
echo                ║[94mTikTok: [37mhttps://www.tiktok.com/@%username%
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mInstagram: [37mhttps://www.instagram.com/%username%             
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mFacebook: [37mhttps://www.facebook.com/%username%               
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mTwitter: [37mhttps://www.twitter.com/%username%                 
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mSteam: [37mhttps://steamcommunity.com/id/%username%             
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mYouTube: [37mhttps://www.youtube.com/user/%username%            
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mGitHub: [37mhttps://www.github.com/%username%                   
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mReddit: [37mhttps://www.reddit.com/user/%username%              
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mDiscord: [37mhttps://www.discord.com/%username%                 
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mSoundCloud: [37mhttps://soundcloud.com/%username%               
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mTwitch: [37mhttps://www.twitch.tv/%username%                   
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mSnapchat: [37mhttps://www.snapchat.com/add/%username%           
echo                [37m║════════════════════════════════════════════════════════════
echo                ║[94mPinterest: [37mhttps://www.pinterest.com/%username%             
echo                [37m╚════════════════════════════════════════════════════════════
pause
goto :menu


:scanIPRange
cls
echo                                    [96m(   .      )    
echo                                    [96m.; )  ' (( (
echo                                    [96m_"., ,._'_
echo                           [96m; )  ' (╔══════════╗ ; )  ' (
echo                          [96m"., ,._' ║  Pscan   ║ "., ,._'
echo                          [96m╔════════╚══════════╝════════╗ 
echo                          [96m║         Ip Address         [96m║
echo                          [96m╚════════════════════════════╝ 

echo                     .  ; )  ' (( (" )    ;(.; )  ' (( (" ) 
echo                          _"., ,._'_.,)__"., ,_"., ,._'_.,)__
echo                         ┌─┐┌─┐┬─┐┌┬┐  ┌─┐┌─┐┌─┐┌┐┌┌┐┌┌─┐┬─┐
echo                         ├─┘│ │├┬┘ │   └─┐│  ├─┤││││││├┤ ├┬┘
echo                         ┴  └─┘┴└─ ┴   └─┘└─┘┴ ┴┘└┘┘└┘└─┘┴└─
set /p ipRange=


echo %ipRange% | findstr /r /i /c:"^\([0-9]\{1,3\}\.\)\{3\}[0-9]\{1,3\}$" >nul 2>&1
if %errorlevel% equ 0 (
    nmap -p- -T4 -Pn %ipRange%
) else (
    nmap --top-ports 100 -T4 -Pn %ipRange%
)

if %errorlevel% neq 0 (
    echo An error occurred while scanning the IP range. Please check the input and try again.
    pause
    goto scanIPRange
) else (
    pause
    goto menu
)

:dos_ip
echo                [33m...                                
echo              [33m;::::;                              
echo            [33m;::::; :;                              
echo          [33m;:::::'   :;                             
echo         [33m;:::::;     ;.                           
echo        [33m,:::::'       ;           [33m.OOO\           
echo        [33m::::::;       ;          [33m.OOOOO\            
echo        [33m;:::::;       ;         [33m.OOOOOOOO           
echo       [33m,;::::::;     ;'         [33m./ [33mOOOOOOO          
echo     [33m;:::::::::`. ,,,;.        [33m./  [33m/ [33mDOOOOOO        
echo   [33m.';:::::::::::::::::;,     [33m./  [33m/     [33mDOOOO     
echo  [33m,::::::;::::::;;;;::::;,   [33m/  [33m/        [33mDOOO     
echo [33m;`::::::`'::::::;;;::::: ,#[33m/  [33m/          [33mDOOO   
echo [33m:`:::::::`;::::::;;::: ;::#  [33m/            [33mDOOO   
echo [33m::`:::::::`;:::::::: ;::::# [33m/              [33mDOO   
echo [33m`:`:::::::`;:::::: ;::::::#[33m/               [33mDOO
echo  [33m:::`:::::::`;; ;:::::::::##                [33mOO
echo  [33m::::`:::::::`;::::::::;:::#                [33mOO
echo  [33m`:::::`::::::::::::;'`:;::#                [33mO
echo   [33m`:::::`::::::::;' [33m/  [33m/ `:#
echo    [33m::::::`:::::;'  [33m/  [33m/   `#  
echo [33m╔╦╗╔═╗╔═╗  ╔═╗╔╦╗╔╦╗╔═╗╔═╗╦╔═
echo  [33m║║║ ║╚═╗  ╠═╣ ║  ║ ╠═╣║  ╠╩╗
echo [33m═╩╝╚═╝╚═╝  ╩ ╩ ╩  ╩ ╩ ╩╚═╝╩ ╩
set /p ip_address=Enter Local ip address: 
set /p num_requests=Enter the number of requests to send: 
echo Sending %num_requests% requests to %ip_address%!
for /l %%i in (1,1,%num_requests%) do (
    echo Request %%i sent to %ip_address%!
    ping -n 1 %ip_address% > nul
)
timeout /t 5
goto :eof

:ipGeoLookup
cls
echo [37m╔═══════════════════════════════╗
echo ║    [94m╦[37m╔═╗  [94m╦  [37m╔═╗[94m╔═╗[37m╦╔═[94m╦ ╦[37m╔═╗[37m   ║
echo ║    [94m║[37m╠═╝  [94m║  [37m║ ║[94m║ ║[37m╠╩╗[94m║ ║[37m╠═╝[37m   ║
echo ║    [94m╩[37m╩    [94m╩═╝[37m╚═╝[94m╚═╝[37m╩ ╩[94m╚═╝[37m╩  [37m   ║
echo [37m╚═══════════════════════════════╝  
set /p "ip=[94mE[37mn[94mt[37me[94mr [37ma[94mn [37mI[94mP [37ma[97m[37md[97md[37mre[97ms[37ms: "             
echo.
curl -s ipinfo.io/%ip% | findstr /R /C:"\"city\":" /C:"\"postal\":" /C:"\"country\":" /C:"\"loc\":" /C:"\"timezone\":"
echo.
echo [94m╚═════════════════════════════════════════════
pause
exit /b
