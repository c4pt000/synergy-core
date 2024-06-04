# Synergy Core
# (synergy has deep rooted security problems via infections through dlls, dylibs, *DO NOT USE* , USE AT YOUR RISK)
similar to DLL hijacking and packing for system32 injection,
https://www.virusbulletin.com/virusbulletin/2015/03/dylib-hijacking-os-x

# building

```
yum install libxkbfile-devel libnotify-devel cmake -y
mkdir build
cd build
cmake ..
make -j24
make -j24 install
```

# compile activator

```
g++ -o activator activator.cpp
```



```
 127.0.0.1:24801        DESKTOP-457FTBM:49714  ESTABLISHED
  TCP    127.0.0.1:49714        DESKTOP-457FTBM:24801  ESTABLISHED
  TCP    192.168.124.233:49598  lb-140-82-114-5-iad:https  TIME_WAIT
  TCP    192.168.124.233:49600  lga25s56-in-f10:https  TIME_WAIT
  TCP    192.168.124.233:53316  doh:https              TIME_WAIT
  TCP    192.168.124.233:58866  doh:https              TIME_WAIT
  TCP    192.168.124.233:62618  10.0.2.2:24800         ESTABLISHED
  TCP    192.168.124.233:62623  52.177.165.30:https    ESTABLISHED
  TCP    192.168.124.233:62628  a23-38-167-219:http    ESTABLISHED
  TCP    192.168.124.233:63458  204.79.197.219:https   TIME_WAIT
  
  
  http://204.79.197.219/
  
  https://www.abuseipdb.com/check/52.177.165.30
  
  
  nmap 52.177.165.30
Starting Nmap 7.80 ( https://nmap.org ) at 2021-07-10 21:06 EDT
Nmap scan report for 52.177.165.30
Host is up (0.016s latency).
Not shown: 999 filtered ports
PORT    STATE SERVICE
443/tcp open  https

Nmap done: 1 IP address (1 host up) scanned in 4.37 seconds

  ```



# AS PART OF THE FREE LICENSE I CAN CHANGE THIS, EDIT IT, even the activation,

use at your own risk (synergy previously had a clipboard exploit internally in the software of synergy, that effected my computer 4 years ago with copy and paste injection)



https://raw.githubusercontent.com/symless/synergy-core/master/LICENSE

```
Copyright (C) 1989, 1991 Free Software Foundation, Inc.,
 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.
 
 
  1. You may copy and distribute verbatim copies of the Program's
source code as you receive it, in any medium, provided that you
conspicuously and appropriately publish on each copy an appropriate
copyright notice and disclaimer of warranty; keep intact all the
notices that refer to this License and to the absence of any warranty;
and give any other recipients of the Program a copy of this License
along with the Program.

You may charge a fee for the physical act of transferring a copy, and
you may at your option offer warranty protection in exchange for a fee.

  2. You may modify your copy or copies of the Program or any portion
of it, thus forming a work based on the Program, and copy and
distribute such modifications or work under the terms of Section 1
above, provided that you also meet all of these conditions:
```
