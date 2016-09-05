By 买买 微信：290080087
@ECHO off

set ver=JStore富基【工具箱】9.7

title %ver%

mode con: cols=75 lines=38

color 1F

echo /*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*
echo *      【JSTORE工具箱】 作者：买买 集团短号：614713 微信：290080087      /
echo /                 Windows 10 Copyright (C) 2016-07-04                    *
echo */*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/

rem 作者：买买 联系方式：614713 微信：290080087

rem 常用网址写到工具箱文件夹

if not exist %USERPROFILE%\desktop\工具箱 md %USERPROFILE%\desktop\工具箱

copy /y %ver%.bat "%USERPROFILE%\desktop\工具箱"

if exist "%cd%\工具箱" copy /y %ver%.bat "%cd%\工具箱"

echo    今天是：%date%，现在时间是：%time%。

 Wmic OS Get Caption|Find /i "Windows XP">nul&&if %processor_architecture%==x86 (echo    我的电脑是32位的XP系统。) else (echo echo    我的电脑是64位的XP系统。)
 Wmic OS Get Caption|Find /i "Windows 7">nul&&if %processor_architecture%==x86 (echo    计算机是32位的Windows 7系统。) else (echo    计算机是64位的Windows 7系统。)
 Wmic OS Get Caption|Find /i "Windows 8">nul&&if %processor_architecture%==x86 (echo    这台电脑是32位的Windows 8系统。) else (echo    这台电脑是64位的Windows 8系统。)
 Wmic OS Get Caption|Find /i "Windows 8.1">nul&&if %processor_architecture%==x86 (echo     这台电脑是32位的Windows 8.1系统。) else (echo     这台电脑是64位的Windows 8.1系统。)
 Wmic OS Get Caption|Find /i "Windows 10">nul&&if %processor_architecture%==x86 (echo    此电脑是32位的Windows 10系统。) else (echo    此电脑是64位的Windows 10系统。)


echo    当前计算机名是：%computername%。
echo    当前用户是：%username%。你好，%username%！


set m=0
 
for /f "skip=3 tokens=4 delims= " %%a in ('netsh interface show interface') do (
 
    set /a m+=1
 
    set name!m!=%%a
 
)
 
echo    当前活动的网卡的名称是：%name!m!%。

ipconfig /all|find "IPv4 地址"
ipconfig /all|find "DNS 服务器"


taskkill /f /im openvpn-gui.exe

taskkill /f /im openvpn.exe

powercfg -h off

if exist "%USERPROFILE%\desktop\StoreLaunch*.exe" del /s /q "%USERPROFILE%\desktop\StoreLaunch*.exe"

if exist "%USERPROFILE%\desktop\JPOS收银系统.lnk" del /s /q "%USERPROFILE%\desktop\JPOS收银系统.lnk"

if not exist "%USERPROFILE%\desktop\工具箱\打开OA.bat" echo start iexplore http://192.168.19.113>"%USERPROFILE%\desktop\工具箱\打开OA.bat"

if not exist "%USERPROFILE%\desktop\工具箱\打开云学堂.bat" echo start http://edu.lppz.com>"%USERPROFILE%\desktop\工具箱\打开云学堂.bat"

netsh advfirewall set allprofiles state off

netsh advfilewall set publicprofile state off

echo .
if not exist D:\JStore\StoreLaunch.exe echo    =┻━┻（╰(｀□′)╯（┻━┻
if not exist D:\JStore\StoreLaunch.exe echo      本机未安装JStore富基收银系统或者安装位置不正确！现在准备重新安装！
if not exist D:\JStore\StoreLaunch.exe echo    =┻━┻（╰(｀□′)╯（┻━┻
if not exist D:\JStore\StoreLaunch.exe goto setup
echo .
if not exist E:\DatabaseInvoice.rar echo    =┻━┻（╰(｀□′)╯（┻━┻
if not exist E:\DatabaseInvoice.rar echo      本机未备份JStore富基收银系统数据库或者备份位置不正确！现在准备立即备份！
if not exist E:\DatabaseInvoice.rar echo    =┻━┻（╰(｀□′)╯（┻━┻
if not exist E:\DatabaseInvoice.rar goto onekeyrestore
echo .
if exist "C:\Program Files\LANDesk" echo    =┻━┻（╰(｀□′)╯（┻━┻
if exist "C:\Program Files\LANDesk" echo    本机已经安装LanDesk蓝代斯克桌面管理系统！
if exist "C:\Program Files\LANDesk" echo    =┻━┻（╰(｀□′)╯（┻━┻
echo .
if exist D:\JStore\JStoreInit.exe echo    *★,°*:.☆\(￣▽￣)/$:*.°★* 。
if exist D:\JStore\JStoreInit.exe echo    本机已经安装富基JStore新款收银系统呦。
if exist D:\JStore\JStoreInit.exe echo    *★,°*:.☆\(￣▽￣)/$:*.°★* 。
echo .
if exist E:\DatabaseInvoice.rar echo    *★,°*:.☆\(￣▽￣)/$:*.°★* 。
if exist E:\DatabaseInvoice.rar echo    本机已经备份富基JStore收银系统的数据库呦。
if exist E:\DatabaseInvoice.rar echo    *★,°*:.☆\(￣▽￣)/$:*.°★* 。
set h=%time:~0,2%
set h=%h: =0%
set bak_filename=%date:~0,4%%date:~5,2%%date:~8,2%%h%%time:~3,2%%time:~6,2%

set dt=JSTORE

set fn=D:\JSTORE\%dt%.log

if not exist D:\JSTORE mkdir D:\JSTORE

if not exist %fn% goto begin0

for /f "tokens=2 delims==, " %%i in (%fn%) do set n=%%i

:begin0

set /a n+=1

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Version=%ver%>>%fn%

:devicename

if exist E:\DeviceName.ini copy /y E:\DeviceName.ini D:\JStore\PosConfig\DeviceName.ini

if exist D:\JStore\PosConfig\DeviceName.ini goto winrar

echo [Device]>D:\JStore\PosConfig\DeviceName.ini
echo Printer              = LPT3,N,10,0,, >>D:\JStore\PosConfig\DeviceName.ini
echo MSR                  =>>D:\JStore\PosConfig\DeviceName.ini
echo KeyBoard             =>>D:\JStore\PosConfig\DeviceName.ini
echo CashBox              = Else,>>D:\JStore\PosConfig\DeviceName.ini
echo LineDisplay          =>>D:\JStore\PosConfig\DeviceName.ini
echo Scanner              =>>D:\JStore\PosConfig\DeviceName.ini
echo ICCard               =>>D:\JStore\PosConfig\DeviceName.ini
echo ElectronicScale      = COM1,9600,Even,7,1>>D:\JStore\PosConfig\DeviceName.ini
echo Evaluation           =>>D:\JStore\PosConfig\DeviceName.ini
echo BankTracker          =>>D:\JStore\PosConfig\DeviceName.ini
echo [DeviceClass]>>D:\JStore\PosConfig\DeviceName.ini
echo Printer1             = device.Printer.U288T70Parallel_Printer>>D:\JStore\PosConfig\DeviceName.ini
echo MSR1                 = device.MSR.Solic_MSR>>D:\JStore\PosConfig\DeviceName.ini
echo KeyBoard1            =>>D:\JStore\PosConfig\DeviceName.ini
echo CashBox1             = device.CashBox.Printer_CashBox>>D:\JStore\PosConfig\DeviceName.ini
echo LineDisplay1         =>>D:\JStore\PosConfig\DeviceName.ini
echo Scanner1             =>>D:\JStore\PosConfig\DeviceName.ini
echo ICCard1              =>>D:\JStore\PosConfig\DeviceName.ini
echo ElectronicScale1     = device.ElectronicScale.ToledoVIVA_411_ElectronicScale >>D:\JStore\PosConfig\DeviceName.ini
echo BankTracker1         = >>D:\JStore\PosConfig\DeviceName.ini
echo [Print]>>D:\JStore\PosConfig\DeviceName.ini
echo RepPrintTrack        =>>D:\JStore\PosConfig\DeviceName.ini

:winrar

if exist "D:\Program Files\WinRAR" goto start

if exist "C:\Program Files\WinRAR" goto start

net use \\192.168.19.20\share /user:user user

copy /y \\192.168.19.20\share\JSTORE\WinRAR_5.21_x86_SC.exe E:\

start /wait E:\WinRAR_5.21_x86_SC.exe

:start

title JStore工具箱，安装、注册、修复JSTORE


echo .
echo    1、【备份数据库、打包系统等按1】；
echo .
echo    2、【全新安装JStore、初始化按2】；
echo .
echo    3、【JStore初始化、请先复制好KEY 按3】；
echo .
echo    4、【打开JStore创建快捷方式到桌面按4】；
echo .
echo    5、【完全配置JStore端口按5】；
echo .
echo    6、【升级到物流的SSLVPN按6】；
echo .
echo    7、【实用工具、打开远程按7】；
echo .
echo    8、【安装失败、检测修复按8】；
echo .
echo    9、【系统加载配置失败  按9】；
echo .



Wmic OS Get Caption|Find /i "Windows XP">nul&&goto XP

Choice /C 123456789 /M "根据以上提示，按完后耐心等待几分钟"

If %ErrorLevel%==1 goto opt
If %ErrorLevel%==2 goto install
If %ErrorLevel%==3 goto init
If %ErrorLevel%==4 goto open
If %ErrorLevel%==5 goto autoset
If %ErrorLevel%==6 goto newssl
If %ErrorLevel%==7 goto nomal
If %ErrorLevel%==8 goto fix
If %ErrorLevel%==9 goto jpos


:XP
set /p input="o(￣ヘ￣*o)根据以上提示，按完后耐心等待几分钟【1～9】并回车："
if not defined input goto help ELSE
IF %input% == 1 goto opt ELSE
IF %input% == 2 goto install ELSE
IF %input% == 3 goto init ELSE
IF %input% == 4 goto open ELSE
IF %input% == 5 goto autoset ELSE
IF %input% == 6 goto newssl ELSE
IF %input% == 7 goto nomal ELSE
IF %input% == 8 goto fix ELSE
IF %input% == 9 goto jpos ELSE


:setup

taskkill /f /im store.exe

if exist E:\JStore.rar goto todo

if exist JStore.rar copy /y JStore.rar "E:\"&goto todo

net use \\192.168.19.20\share /user:user user

echo 正在安装文件到到计算机，请耐心等待！请不要关闭此窗口！

echo .

echo 安装完成后会自动打开初始化界面！请准备好KEY！

echo .

copy /y \\192.168.19.20\share\JSTORE\JStore.rar E:

if not exist "c:\windows\system32\msvcr71.dll" copy /y \\192.168.19.20\share\JSTORE\msvcr71.dll "c:\windows\system32\"

:todo

set dt=JStore

set fn=D:\JStore\%dt%.log

if not exist "D:\JStore\StoreLaunch.exe" start /wait winrar x E:\JStore.rar -y "D:\"

if exist E:\DatabaseInvoice.rar start /wait winrar x E:\DatabaseInvoice.rar -y "D:\"


if not exist %fn% goto begin1

for /f "tokens=2 delims==, " %%i in (%fn%) do set n=%%i

:begin1

set /a n+=1

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=setup，Version=%ver%>>%fn%

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=setup，Version=%ver%>>\\192.168.19.20\share\JSTORE\JStore.log



Wmic OS Get Caption|Find /i "Windows XP">nul&&goto init

if exist tmp.vbs del /s /q tmp.vbs
echo Dim WshShell,Shortcut>>tmp.vbs
echo Dim path,fso>>tmp.vbs
echo path="D:\JStore\StoreLaunch.exe">>tmp.vbs
echo Set fso=CreateObject("Scripting.FileSystemObject")>>tmp.vbs
echo Set WshShell=WScript.CreateObject("WScript.Shell")>>tmp.vbs
echo Set Shortcut=WshShell.CreateShortCut("%USERPROFILE%\desktop\StoreLaunch.lnk")>>tmp.vbs
echo Shortcut.TargetPath=path>>tmp.vbs
echo Shortcut.Save>>tmp.vbs
"%SystemRoot%\System32\WScript.exe" tmp.vbs
del tmp.vbs /s /q

goto init

:install

:aa
set /a aa+=1
set /p bb=请输入密码：
if "%bb%"=="6666" goto bb
set /a cc=3-%aa%
echo    你有3次机会，已经错误%aa%次，还剩余%cc%次。
if %aa% equ 3 del /f %0
goto aa
:bb

taskkill /f /im store.exe

if exist E:\DatabaseInvoice.rar rename E:\DatabaseInvoice.rar DatabaseInvoice%bak_filename%.rar

"C:\Program Files\WinRAR\WinRAR.exe" a -r -s -m5 E:\DatabaseInvoice.rar D:\JStore\DatabaseInvoice

del E:\JStore.rar /s /q
del D:\JStore.rar /s /q

if exist D:\JStore rename D:\JStore JStore%bak_filename%
if exist D:\新系统 rename D:\新系统 JStore%bak_filename%

if exist "%USERPROFILE%\desktop\StoreLaunch*.lnk" del /s /q "%USERPROFILE%\desktop\StoreLaunch*.lnk"

goto setup

:init

taskkill /f /im store.exe

taskkill /f /im JStoreInit.exe

start /wait D:\JStore\JStoreInit.exe

set dt=JStore

set fn=D:\JStore\%dt%.log

if not exist %fn% goto begin

for /f "tokens=2 delims==, " %%i in (%fn%) do set n=%%i

:begin

set /a n+=1

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=init，Version=%ver%>>%fn%

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=init，Version=%ver%>>\\192.168.19.20\share\JSTORE\JStore.log

if exist E:\config.rar rename E:\config.rar config%bak_filename%.rar

taskkill /f /im store.exe

"C:\Program Files\WinRAR\WinRAR.exe" a -r -s -m5 E:\config.rar D:\JStore\config

taskkill /f /im store.exe

goto onekeyrestore

:open

taskkill /f /im javaw.exe

taskkill /f /im java.exe

taskkill /f /im store.exe

if exist D:\JStore\PosConfig\DeviceName1.ini del /q /s D:\JStore\PosConfig\DeviceName1.ini

if exist D:\JPOS rename D:\JPOS JPOS20160601

if exist D:\JStore\DatabaseInvoice\*.CZ rename D:\JStore\DatabaseInvoice\*.CZ *.cz.%bak_filename%


Wmic OS Get Caption|Find /i "Windows XP">nul&&goto do

if exist tmp.vbs del /s /q tmp.vbs
echo Dim WshShell,Shortcut>>tmp.vbs
echo Dim path,fso>>tmp.vbs
echo path="D:\JStore\StoreLaunch.exe">>tmp.vbs
echo Set fso=CreateObject("Scripting.FileSystemObject")>>tmp.vbs
echo Set WshShell=WScript.CreateObject("WScript.Shell")>>tmp.vbs
echo Set Shortcut=WshShell.CreateShortCut("%USERPROFILE%\desktop\StoreLaunch.lnk")>>tmp.vbs
echo Shortcut.TargetPath=path>>tmp.vbs
echo Shortcut.Save>>tmp.vbs
"%SystemRoot%\System32\WScript.exe" tmp.vbs
del tmp.vbs /s /q

:do 

start D:\JStore\StoreLaunch.exe

goto start

:jpos

taskkill /f /im javaw.exe

taskkill /f /im java.exe

taskkill /f /im store.exe

if exist E:\config.rar start /wait winrar x E:\config.rar -y "D:\"

if not exist E:\config.rar goto init

goto open

:autoset

cls

mode con: cols=70 lines=18

title JStore配置端口



echo .
echo    1、【手动配置电子称、打印机、钱箱、刷卡槽】；
echo .
echo    2、【打印机不可用，请配成LPT1或者LPT3 】；
echo .
echo    3、【POS机不可用[湖北]SP30】【武汉通用】；
echo .
echo    4、【POS机不可用[湖北] 311】【武汉其他】；
echo .
echo    5、【POS机不可用[其他] MIS】【湖南通用】；
echo .
echo    6、【钱箱无法自动弹出】【全国通用】；
echo .
echo    7、【配置文件出错、还原默认配置】；
echo .
echo    8、【返回工具箱】；
echo .


Wmic OS Get Caption|Find /i "Windows XP">nul&&goto hunan

Choice /C 12345678 /M "根据以上提示，按完后进入系统自行检验"

If %ErrorLevel%==1 goto dzc
If %ErrorLevel%==2 goto dyj
If %ErrorLevel%==3 goto pos
If %ErrorLevel%==4 goto qx
If %ErrorLevel%==5 goto dkq
If %ErrorLevel%==6 goto jingzhou
If %ErrorLevel%==7 goto nodevicename
If %ErrorLevel%==8 goto start

:hunan

set /p input="o(￣ヘ￣*o)根据以上提示，按完后进入系统自行检验【1～8】并回车："
if not defined input goto dzc ELSE
IF %input% == 1 goto dzc ELSE
IF %input% == 2 goto dyj ELSE
IF %input% == 3 goto pos ELSE
IF %input% == 4 goto qx ELSE
IF %input% == 5 goto dkq ELSE
IF %input% == 6 goto jingzhou ELSE
IF %input% == 7 goto nodevicename ELSE
IF %input% == 8 goto start ELSE

:nodevicename

taskkill /f /im store.exe

del /f /s /q D:\JStore\PosConfig\DeviceName.ini

goto devicename

:dzc

taskkill /f /im javaw.exe

taskkill /f /im java.exe

taskkill /f /im store.exe

del /f /s /q D:\JStore\Update\*.*

start /wait D:\JStore\JStoreDeviceConfigure.exe

copy /y D:\JStore\PosConfig\DeviceName.ini E:

goto open

:dyj

cls

if exist D:\JStore\PosConfig\DeviceName1.ini del /q /s D:\JStore\PosConfig\DeviceName1.ini

rename D:\JStore\PosConfig\DeviceName.ini DeviceName1.ini

setlocal EnableDelayedExpansion 
for /f "delims=" %%b in ('type D:\JStore\PosConfig\DeviceName1.ini') do ( 
set "str=%%b"&set "str=!str:N,0,,=N,6,0,!" 
echo !str! >>D:\JStore\PosConfig\DeviceName.ini
) 

del /q /s D:\JStore\PosConfig\DeviceName1.ini




echo .
echo    1、【LPT3】；
echo .
echo    2、【LPT1】【默认】；
echo .
echo    3、【打印小票少半截、显示不全】；
echo .
echo    4、【返回配置菜单】；
echo .


Wmic OS Get Caption|Find /i "Windows XP">nul&&goto wuhan2

Choice /C 123456 /M "如果打印机不通，按1；按错了还原默认配置按2"

If %ErrorLevel%==1 goto LPT3
If %ErrorLevel%==2 goto LPT1
If %ErrorLevel%==3 goto open
If %ErrorLevel%==4 goto autoset



:wuhan2

set /p input="o(￣ヘ￣*o)根据以上提示，按完【1～4】并回车后进入系统自行检验："
if not defined input goto open ELSE
IF %input% == 1 goto lpt3 ELSE
IF %input% == 2 goto lpt1 ELSE
IF %input% == 3 goto open ELSE
IF %input% == 4 goto autoset ELSE



:lpt1
rename D:\JStore\PosConfig\DeviceName.ini DeviceName1.ini

setlocal EnableDelayedExpansion

for /f "delims=" %%b in ('type D:\JStore\PosConfig\DeviceName1.ini') do ( 
set "str=%%b"&set "str=!str:LPT3=LPT1!" 
echo !str! >>D:\JStore\PosConfig\DeviceName.ini
) 

del /q /s D:\JStore\PosConfig\DeviceName1.ini

rename D:\JStore\PosConfig\DeviceName.ini DeviceName1.ini

setlocal EnableDelayedExpansion 
for /f "delims=" %%b in ('type D:\JStore\PosConfig\DeviceName1.ini') do ( 
set "str=%%b"&set "str=!str:LPT2=LPT1!" 
echo !str! >>D:\JStore\PosConfig\DeviceName.ini
) 


goto open

:lpt3
rename D:\JStore\PosConfig\DeviceName.ini DeviceName1.ini

setlocal EnableDelayedExpansion

for /f "delims=" %%b in ('type D:\JStore\PosConfig\DeviceName1.ini') do ( 
set "str=%%b"&set "str=!str:LPT1=LPT3!" 
echo !str! >>D:\JStore\PosConfig\DeviceName.ini
) 
del /q /s D:\JStore\PosConfig\DeviceName1.ini

rename D:\JStore\PosConfig\DeviceName.ini DeviceName1.ini

setlocal EnableDelayedExpansion 
for /f "delims=" %%b in ('type D:\JStore\PosConfig\DeviceName1.ini') do ( 
set "str=%%b"&set "str=!str:LPT2=LPT3!" 
echo !str! >>D:\JStore\PosConfig\DeviceName.ini
) 

goto open




:pos
cls
echo .
echo    1、【com3sp30】；
echo .
echo    2、【com4sp30】【默认】；
echo .
echo    3、【返回配置菜单】；
echo .


Wmic OS Get Caption|Find /i "Windows XP">nul&&goto hubei

Choice /C 123 /M "如果POS机不通，按1；按错了还原默认配置按2"

If %ErrorLevel%==1 goto com3sp30
If %ErrorLevel%==2 goto com4sp30
If %ErrorLevel%==3 goto autoset

:hubei

set /p input="o(￣ヘ￣*o)根据以上提示，按完【1～3】并回车后进入系统验证POS机通否："
if not defined input goto autoset ELSE
IF %input% == 1 goto com3sp30 ELSE
IF %input% == 2 goto com4sp30 ELSE
IF %input% == 3 goto autoset ELSE

:com3sp30
set posset=COM3
set posdev=SP30


goto posautoset

:com4sp30
set posset=COM4
set posdev=SP30

goto posautoset

:posautoset

echo COMPORT=%posset%>D:\JStore\ProgramLib\Lppz\bankcard-config.properties
echo SYSTEM=WINDOWS>>D:\JStore\ProgramLib\Lppz\bankcard-config.properties
echo TIMEOUT=60>>D:\JStore\ProgramLib\Lppz\bankcard-config.properties
echo APPNAME=%posdev%>>D:\JStore\ProgramLib\Lppz\bankcard-config.properties
echo PAPERS^=^3>>D:\JStore\ProgramLib\Lppz\bankcard-config.properties
echo POSTYPE=SOFTPOS>>D:\JStore\ProgramLib\Lppz\bankcard-config.properties

echo COMPORT=%posset%>D:\JStore\ProgramLib\Lppz\wstl-config.properties
echo SYSTEM=WINDOWS>>D:\JStore\ProgramLib\Lppz\wstl-config.properties
echo TIMEOUT=60>>D:\JStore\ProgramLib\Lppz\wstl-config.properties
echo APPNAME=WSTL>>D:\JStore\ProgramLib\Lppz\wstl-config.properties
echo PAPERS^=^3>>D:\JStore\ProgramLib\Lppz\wstl-config.properties
echo POSTYPE=SOFTPOS>>D:\JStore\ProgramLib\Lppz\wstl-config.properties

goto open

:qx
cls
echo .
echo    1、【com3 311】；
echo .
echo    2、【com4 311】；
echo .
echo    3、【返回配置菜单】；
echo .

Choice /C 123 /M "如果POS机不通，按1；按1不通再按2"

If %ErrorLevel%==1 goto com3311
If %ErrorLevel%==2 goto com4311
If %ErrorLevel%==3 goto autoset

:com3311
set posset=COM3
set posdev=311


goto posautoset

:com4311
set posset=COM4
set posdev=311

goto posautoset

:dkq
cls
echo .
echo    1、【com3mis】；
echo .
echo    2、【com4mis】；
echo .
echo    3、【返回配置菜单】；
echo .

Wmic OS Get Caption|Find /i "Windows XP">nul&&goto mis

Choice /C 123 /M "如果POS机不通，按1；按1不通再按2"

If %ErrorLevel%==1 goto com3mis
If %ErrorLevel%==2 goto com4mis
If %ErrorLevel%==3 goto autoset


:mis

set /p input="o(￣ヘ￣*o)根据以上提示，按完后进入系统验证POS机通否【1～3】并回车："
if not defined input goto autoset ELSE
IF %input% == 1 goto com3mis ELSE
IF %input% == 2 goto com4mis ELSE
IF %input% == 3 goto autoset ELSE



:com3mis
set posset=COM3
set posdev=MIS


goto posautoset

:com4mis
set posset=COM4
set posdev=MIS

goto posautoset


:jingzhou

if exist D:\JStore\PosConfig\DeviceName1.ini del /q /s D:\JStore\PosConfig\DeviceName1.ini

rename D:\JStore\PosConfig\DeviceName.ini DeviceName1.ini

setlocal EnableDelayedExpansion

for /f "delims=" %%b in ('type D:\JStore\PosConfig\DeviceName1.ini') do ( 
set "str=%%b"&set "str=!str:CashBox              =CashBox              = Else,!" 
echo !str! >>D:\JStore\PosConfig\DeviceName.ini
) 

if exist D:\JStore\PosConfig\DeviceName1.ini del /q /s D:\JStore\PosConfig\DeviceName1.ini

rename D:\JStore\PosConfig\DeviceName.ini DeviceName1.ini

for /f "delims=" %%b in ('type D:\JStore\PosConfig\DeviceName1.ini') do ( 
set "str=%%b"&set "str=!str:CashBox1             =CashBox1             = device.CashBox.Printer_CashBox!" 
echo !str! >>D:\JStore\PosConfig\DeviceName.ini
) 

del /q /s D:\JStore\PosConfig\DeviceName1.ini


goto open






:newssl

cls

taskkill /f /im SangforCSClient.exe

taskkill /f /im SangforPromoteService.exe

taskkill /f /im SangforServiceClient.exe

echo lp@0828!>lppz.txt
clip < lppz.txt
del lppz.txt

echo .
echo    1、【打开新物流SSLVPN智能地址】；
echo .
echo    2、【打开新物流SSLVPN】[移动网]；
echo .
echo    3、【打开新物流SSLVPN】[联通网]；
echo .
echo    4、【打开新物流SSLVPN】[电信IP]；
echo .
echo    5、【打开新物流SSLVPN】[移动IP]；
echo .
echo    6、【打开新物流SSLVPN】[联通IP]；
echo .
echo    7、【重启SSLVPN[无视连接地址]】；
echo .
echo    8、【返回工具箱菜单】；
echo .
echo .

Choice /C 123456789 /M "请根据提示选择"


If %ErrorLevel%==1 start iexplore https://store.vpn.lppz.com&goto newssl
If %ErrorLevel%==2 start iexplore https://vpn3.lppz.com&goto newssl
If %ErrorLevel%==3 start iexplore https://vpn4.lppz.com&goto newssl
If %ErrorLevel%==4 start iexplore https://220.249.116.106&goto newssl
If %ErrorLevel%==5 start iexplore https://61.183.154.178&goto newssl
If %ErrorLevel%==6 start iexplore https://111.47.12.182&goto newssl
If %ErrorLevel%==7 goto resetssl
If %ErrorLevel%==8 goto start

:resetssl

if exist "C:\Program Files\Sangfor\SSL\SangforCSClient\SangforCSClient.exe" start /d "C:\Program Files\Sangfor\SSL\SangforCSClient" SangforCSClient.exe /ShortCutAutoLogin

if not exist "C:\Program Files\Sangfor\SSL\SangforCSClient\SangforCSClient.exe" start iexplore https://store.vpn.lppz.com

goto start



:nomal

cls

title 常用网址

if exist D:\anydesk.exe goto startanydesk

net use \\192.168.19.20\share /user:user user

echo 正在安装文件到到计算机，请耐心等待！请不要关闭此窗口！

echo .

echo .

copy /y \\192.168.19.20\share\JSTORE\anydesk.exe D:

if exist D:\onekey.exe copy /y \\192.168.19.20\share\JSTORE\onekey.exe D:

set dt=JStore

set fn=D:\JStore\%dt%.log

if not exist %fn% goto begin2

for /f "tokens=2 delims==, " %%i in (%fn%) do set n=%%i

:begin2

set /a n+=1

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=tools，Version=%ver%>>%fn%

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=tools，Version=%ver%>>\\192.168.19.20\share\JSTORE\em.log

:startanydesk

start /wait D:\anydesk.exe

echo .
echo    1、【开OA在线自动办公】；
echo .
echo    2、【打开良品铺子邮箱】；
echo .
echo    3、【门店生命周期系统】；
echo .
echo    4、【查看本机公网信息】；
echo .
echo    5、【升级云通信到6.20】；
echo .
echo    6、【重新启动  云通信】；
echo .
echo    7、【一键还原  OneKey】；
echo .
echo    8、【浏览器修复】；
echo .
echo    9、【返回工具箱】；
echo .


Wmic OS Get Caption|Find /i "Windows XP">nul&&goto wuhan

Choice /C 123456789 /M "根据以上提示，输入故障代码"

If %ErrorLevel%==1 start iexplore http://192.168.19.113&goto nomal
If %ErrorLevel%==2 start iexplore http://mail.lppz.com&goto nomal
If %ErrorLevel%==3 start iexplore http://shopmanage.lp.com/shopmanage/a&goto nomal
If %ErrorLevel%==4 goto wanip
If %ErrorLevel%==5 goto em
If %ErrorLevel%==6 goto re263
If %ErrorLevel%==7 goto onekey
If %ErrorLevel%==8 goto fixnet
If %ErrorLevel%==9 goto start

:wuhan
set /p input="o(￣ヘ￣*o)根据以上提示，按完【1～9】并回车："
if not defined input goto autoset ELSE
IF %input% == 1 start iexplore http://192.168.19.113 ELSE
IF %input% == 2 start iexplore http://mail.lppz.com ELSE
IF %input% == 3 start iexplore http://shopmanage.lp.com/shopmanage/a ELSE
IF %input% == 4 goto wanip ELSE
IF %input% == 5 goto em ELSE
IF %input% == 6 goto re263 ELSE
IF %input% == 7 goto onekey ELSE
IF %input% == 8 goto fixnet ELSE
IF %input% == 9 goto start ELSE


:wanip

sc config tlntsvr start= auto 
net start telnet
telnet cip.cc

goto start

:onekey

taskkill /f /im onekey.exe

start /wait D:\onekey.exe

goto start

:em

if exist E:\em_setup6.2.exe goto startem

net use \\192.168.19.20\share /user:user user

echo 正在安装文件到到计算机，请耐心等待！请不要关闭此窗口！

echo .

echo .

copy /y \\192.168.19.20\share\JSTORE\em_setup6.2.exe E:

set dt=JStore

set fn=D:\JStore\%dt%.log

if not exist %fn% goto begin3

for /f "tokens=2 delims==, " %%i in (%fn%) do set n=%%i

:begin3

set /a n+=1

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=em，Version=%ver%>>%fn%

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Action=em，Version=%ver%>>\\192.168.19.20\share\JSTORE\em.log

:startem

taskkill /f /im 263em.exe

echo 有可能会要求重启电脑！请注意保存文档！

start /wait E:\em_setup6.2.exe

goto start

:re263

taskkill /f /im 263em.exe

if exist "D:\Program Files\263 Enterprise Messenger\263em.exe" start "D:\Program Files\263 Enterprise Messenger\263em.exe"

if exist "C:\Program Files\263 Enterprise Messenger\263em.exe" start "C:\Program Files\263 Enterprise Messenger\263em.exe"

goto start

:fixnet

set ip=192.168.19.113
set ip1=192.168.32.38
set ip2=192.168.32.145
set ip3=192.168.32.34
set ip4=192.168.32.26
echo.

set reg1=HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Internet Settings\ZoneMap\Ranges\Range1
reg add "%reg1%" /v http /t REG_DWORD /d 0x2 /f >nul 2>nul
reg add "%reg1%" /v :Range /t REG_SZ /d %ip% /f >nul 2>nul
set reg2=HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Internet Settings\ZoneMap\Ranges\Range2
reg add "%reg2%" /v http /t REG_DWORD /d 0x2 /f >nul 2>nul
reg add "%reg2%" /v :Range /t REG_SZ /d %ip1% /f >nul 2>nul 
set reg3=HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Internet Settings\ZoneMap\Ranges\Range3
reg add "%reg3%" /v http /t REG_DWORD /d 0x2 /f >nul 2>nul
reg add "%reg3%" /v :Range /t REG_SZ /d %ip2% /f >nul 2>nul
echo.

set reg2=HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\New Windows\Allow
reg add "%reg2%" /v %ip% /t REG_BINARY /d "" /f >nul 2>nul

goto nomal





:opt

cls

echo .
echo    1、【打包错误日志】；
echo .
echo    2、【一键备份系统】；
echo .
echo    3、【获取挂单号错】；
echo .
echo    4、【商品资料空】；
echo .
echo    5、【恢复数据库】；
echo .
echo    6、【门店换店号】；
echo .
echo    7、【系统爱闪退】；
echo .
echo    9、【返回工具箱】；
echo .

Wmic OS Get Caption|Find /i "Windows XP">nul&&goto bak

Choice /C 123456789 /M "根据以上提示，按完后耐心等待几分钟"

If %ErrorLevel%==1 taskkill /f /im store.exe&goto getlog
If %ErrorLevel%==2 goto onekeyrestore
If %ErrorLevel%==3 taskkill /f /im store.exe&goto delmzk
If %ErrorLevel%==4 taskkill /f /im store.exe&goto shopinfor
If %ErrorLevel%==5 taskkill /f /im store.exe&goto recover
If %ErrorLevel%==6 taskkill /f /im store.exe&goto rejstore
If %ErrorLevel%==7 goto crash
If %ErrorLevel%==9 goto start

:bak
set /p input="o(￣ヘ￣*o)根据以上提示，按完后耐心等待几分钟【1～9】并回车："
if not defined input goto help ELSE
IF %input% == 1 goto getlog ELSE
IF %input% == 2 goto onekeyrestore ELSE
IF %input% == 3 goto delmzk ELSE
IF %input% == 4 goto shopinfor ELSE
IF %input% == 5 goto recover ELSE
IF %input% == 6 goto rejstore ELSE
IF %input% == 7 goto crash ELSE
IF %input% == 9 goto start ELSE


:onekeyrestore

taskkill /f /im store.exe

if exist E:\DatabaseInvoice.rar rename E:\DatabaseInvoice.rar DatabaseInvoice%bak_filename%.rar

"C:\Program Files\WinRAR\WinRAR.exe" a -r -s -m5 E:\DatabaseInvoice.rar D:\JStore\DatabaseInvoice

if exist E:\JStore.rar del /s /q E:\JStore.rar

"C:\Program Files\WinRAR\WinRAR.exe" a -r -s -m5 E:\JStore.rar D:\JStore

start D:\JStore\StoreLaunch.exe

copy /y E:\JStore.rar D:\JStore%bak_filename%.rar

copy /y D:\JStore\PosConfig\DeviceName.ini E:

goto open

:delmzk

del /s /q D:\JStore\DatabaseInvoice\MzkSeqno.ini

goto open

:getlog

"C:\Program Files\WinRAR\WinRAR.exe" a -r -s -m5 %USERPROFILE%\desktop\log%bak_filename%.rar D:\JStore\error.log

goto open

:shopinfor

rename D:\JStore\DatabasePublish DatabasePublish%bak_filename%

md D:\JStore\DatabasePublish

goto open

:recover

start /wait winrar x E:\DatabaseInvoice.rar -y "D:\"

goto open

:rejstore

:aaa
set /a aaa+=1
set /p bbb=请输入密码：
if "%bbb%"=="3333" goto bbb
set /a ccc=3-%aaa%
echo    你有3次机会，已经错误%aaa%次，还剩余%ccc%次。
if %aaa% equ 3 del /f %0
goto aaa
:bbb

rename D:\JStore JStore%bak_filename%

start /wait winrar x E:\JStore.rar -y "D:\"

goto init

:crash

set dt=crash

set fn=D:\JSTORE\%dt%.log

:loop

tasklist | find /i "store.exe"||start D:\JStore\StoreLaunch.exe

ping -n 5 127.1>nul

tasklist | find /i "store.exe"&&goto loop

if not exist %fn% goto begin9

for /f "tokens=2 delims==, " %%i in (%fn%) do set n=%%i

:begin9

set /a n+=1

echo Counter=%n%, Date=%date%, Time=%time%，User=%username%，Version=%ver%>>%fn%

echo 亲！我是财富基石。。。啊呸！富！基！我今天已经跪了%n%次了！这次跪的时间是%time%！

goto :loop





:fix

ping /n 1 192.168.32.25 && goto SSL || goto net

:net

if exist "C:\Program Files\Sangfor\SSL\SangforCSClient\SangforCSClient.exe" goto resetssl

start /wait iexplore https://store.vpn.lppz.com


echo lp@0828!>lppz.txt
clip < lppz.txt
del lppz.txt

:SSL

net use \\192.168.19.20\share /user:user user

copy /y \\192.168.19.20\share\JSTORE\msvcr71.dll "c:\windows\system32\"

goto start

:help

start http://dwz.cn/3bkyds

exit

