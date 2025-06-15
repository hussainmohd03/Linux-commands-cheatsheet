# Linux Commands Cheat Sheet

This is a comprehensive and categorized cheat sheet of essential Linux commands. It is intended for system administrators, power users, students, or anyone working in a Linux environment. Commands are grouped by topic and function, with each command highlighted for easy reading.

---

## 📚 Table of Contents
- [General Commands](#general-commands)
- [Managing Users and Groups](#managing-users-and-groups)
- [File Access & Permissions](#file-access--permissions)
- [Disk Partitions and File Systems](#disk-partitions-and-file-systems)
- [Mounting with systemd](#mounting-with-systemd)
- [Logical Volume Manager (LVM)](#logical-volume-manager-lvm)
- [Vi/Vim Editor](#vivim-editor)
- [Searching and Manipulating Files](#searching-and-manipulating-files)
- [Archiving and Compressing](#archiving-and-compressing)
- [Backing up](#backing-up)
- [Scheduling Tasks Using Cron](#scheduling-tasks-using-cron)
- [Boot Process and Kernel](#boot-process-and-kernel)
- [Managing Services](#managing-services)
- [Managing and Configuring Hardware](#managing-and-configuring-hardware)
- [Networking](#networking)
- [Firewall with Firewalld](#firewall-with-firewalld)
- [Security](#security)
- [Installing and Managing Software](#installing-and-managing-software)
- [Git](#git)
- [Capacity Planning](#capacity-planning)

---
2j—Ù:112\
 
2X : 
 
e : Ù2j2Ùe :XÙj\ Ù
\ e X
à
ß
 ÙeX +2 Ùee Ù+
 
+\Ù
ñ
+Ù ï 2ï\
ß

ß
e :Ù\ e Ù\+Ù–:j XÙ\–\e \
 
} \:
Ù

Ù
 :XÙj\ :\j\
Ù
± +àe\ Ù:XX:X\
 
\: Ùää
Ù

Ù
 Ù–:j Ù:X Ùe: Ù\jÙ: XÙej \112
 
e +
Ù

Ù
e :Ù\ Ùe\e ÙP OÙ+ 2 Ù:Ù±+
 
+\\Ù

Ù
e :ÙX + Ù
ü
\:++
 ý
Ù
 
1: X Ù

Ù
e :ÙX + Ù
ü
 U+–\ Ù:2
ý
Ù
 
`wh` i ch
 

 
`locate`  the execu t ablef ile of  a 
`c` o mm and
 
`wh` e re i s
 

 
`locate`  the binary,  sou rce,  a nd manu al pag e f iles  f or a  comm and
 
`t` ype
 

 
`t` o see t he ty pe of  a comm and
 
`who`
 

 
`t` o see w ho is  cu rrent ly l og g ed in
 
`st` at  <fi le  name >
 

 
`dis` play inf o rmation  ab ou t  a f ile
 
`uni` q
 

 
`t` o remove a ny du plicate s  
 
`upt` i me
 

 
`how`  long  the sy s t em has  been o nline
 
`man` 
`-`
`k` <ke ywo rd>
 

 
`f` ind a comm a nd by  a  key w ord
 
 
X\ÙX:j U\
 
 e 2e
Ù
á
Ù
e :ÙX X2:X2Ù X:1Ù
õ õU \\
æßõ õ\:
Ù
2
õ õX:jU
ß
 


 



 
U
\\
Ù
á
Ù
e :Ù
\
Ù
\\ :X :Ùj\
 


 
U\\
Ù
á
Ù
e : \eÙ X:j UÙXee j ¯ÙüÙj\
ñ
Ùe:Ùj\ XÙe:Ù X:j UÙý
 




 








 







 
j\ X
Ù
á
Ù
e :Ùj\Ù
üe:Ù \j +e \ Ùj\
Ù
ñ
 ýÙ
:eç2ß–:jßXeßj\ X :U–ß: ßõeõ\'+ß++ß U+2ß
eXe: X–ß: ßeß2 ßj\X ß
 




 
j\ X +
ÙÙ
á
Ù
e :Ùj\Ù
 




 










 
j\ X1: 
Ù
á
Ù
e :Ù1:Ùj\
Ù
 




 





 











 



 



 
X:jU
Ù
á
Ù
e :e X:jU\
 

 
X:jU1: 
Ù
á
Ù
e :Ù1:Ù X:j UÙüj\
ñ
2Ùe:2
 







 
X:jU +
Ù
á
Ù
e :Ù X:j U
 

 

Ù
á
Ù
e :Ù\\\:X—e2e2 
U:+
 




 










 





 










 
 
X:jU\
Ù
á
Ù
e :Ù\ X:j U\ ÙeeeÙj\:2\ Ùe:ß
 
Ù
á
Ù
 U+–\
à
Ù
2
 X:j U\ Ù:eÙj\ß
 
\Ù
á
Ù
2Ùj\ 
\j +e Ù\+
ßÙ
:eçß
–: jß2ß+\ :ßj\ß
j \X 1ß
÷
\
ß
e:ß2ßeß\+ +
 







 

 
 Ù\\Ù -Ù
2 \
 
\' Ù}\
 

 
O
 
á ÙX X2— e 
 

 
P
 
á ÙX2 X
 

 
Q
 
á ÙX2— e 
 

 
R
 
á ÙX2+–
 

 
S
 
á X2— e 
 

 
T
 
á X2+–
 

 
U
 
á— e2+–
 

 
V
 
á Ù2: X\2\
 
 
Y X e W—je Vß
 
+j\
ß
2 2 j\  2\ ß:Xß1: – 2  + W j+  2ß:Xß:
 X e 2
å —å1 :w X ß± +åe —e
 
 
1 : 
Ù

Ù
e :2\ 2\ Ù
 
 





 





 
:
Ù

Ù
2: 22 X:j UÙ
 





 
XU
Ù

Ù
j \ : 2 X:j UÙ: 2\ 
 




 
U
Ù

Ù
j \ : 2:j XÙUXX – Ù X:j U
 




 
} 2Ù U \\
 
 e+
Ù

Ù
 Ù±+\2e X:+Ù+e \
 


 
`se` t facl
 

 
`s` et  f ile acc es s  cont ro l list s  
 








 










 


 


 
2 \ÙÙ –\e1\
 
`lsbl` k
 

 
`list`  block  devices
 
`blki` d
 

 
`pri` nt  block  devices  at t ribu t es
 
`mkswap`
 
:
 
`cre` at e linu x  sw ap area
 



 
`swapo` n
/swapo f f
 
:
 
`t` o en able
/ dis able
 
`a` sw a p area to beu s ed
 
 



 



 
`mo` unt
 
:
 
`t` o mou nt  a f iles ys t em t o location
 
`N` ot e:
Ù
`if`  youw ant  
`t` hem t obe mount ed aut omat ica llyw he nt he syst em boot s,  
`youw` ill n eed t oa dd t hem t ot he
 
/et c/f st ab
 
`umo` unt
 
:
 
`t` o unmou nt  a f iles ys t em 
 
 
 
j2e Ù Ù\–\e 
 

 
eÙ±+ Ùï eï\–\e 1ï\–\e 1
á
 








 

 
 + Ù
\e Xe jX á
 


 
 

 



 

 
 

 


 





 


 


 


 
 

 



 

 
Ù
 ++Ù\–\e 1Ùe: ÙX XÙj e Ù±+\á
 



 

 
Xe'Ùe Ù\ee j\Ù: Ùe Ù1:j2e á
 



 
 



 

 
:eÙ1:j2ee:: e Ùe á
 



 
 
 Ù ÙXe Ù Ù+
 
`fdi` sk
 
:
 
`u` s ed t o creat e MBR Pa rt ition st yle 
 




 
`gdi` sk
 
:
 
`u` s ed t o creat e GP T pa rt ition st yle
 




 
`part` e d
 
:
 
`u` s ed f or bot h MB R and GP T
 




 
 Ù Ù j Ù Ù –\e 1
 
+\Ùj\Xï\ 2ï1'\ê
ß
á
ß
e :Ù
+e Ù++Ùe +\ Ù: Ù 1'\à ++Ù–:j e Ù±+–\eX
\j UU :Xe 
 
`mkfs`
 
:
 
`t` o bu ild a f iles ys t em
 




 
`e` 2labe l
 
:
 
`t` o cha ng e the labe l
 
`of`  a pa rt ition
 
`on` ext  f iles ys t em
 







 
`xfs_` admi n
 
`-`
`L` 
:
 
`t` o chang e the labe l of  a pa rt i t ion on  xf s  f iles ys t em
 
 






 
X\ ‘ Q\
Ù
á
Ù
j \ :ÙX—e Qïe Rïe SÙ±+ \–\e 
 



 
 Q\'
Ù
á
Ù
 Ùe–\e 
`Not` e:
Ù
`-`
`f`  t of orce check  evenif  cle an
 





 
 :Ù:+j 
Ù
XÙ ü ý
 
 
–Ù:+ j\
 
U}Xe
Ù
á
Ù
XeÙU–\+Ù}:+j2 Ù
 \ ' Ù\:e 
\ ÙX 2\:2 2 Ùe:
 
üÙU}e ï ' PÙï ï ' Qß ß ß ß ß ß Ùý
 
U} \U+–
Ù
á
Ù
 U+–
Ù
:X2j e ÙU–\+Ù}:+j 
 
U}\
Ù
á
Ù
\\ ÙU} U+ eÙ+\2:X2
 
`pvscan`
 
:
 
`s` can  block  devices  f or phys ical v o lu mes
 
`pvre` mo ve
 
:
 
`remove` phys ical volu me f rom l vm
 



 
 
 
 
:+j Ù X:jU\
 
}

Xe
Ù
á
Ù
eÙ}:+j X:j UÙ
 





 
 
} \U+–
Ù
á
Ù
 U+2: X2j e Ù}: +j X:j U\
 
}\
Ù
á
Ù
\\ Ù } U+–
Ù
 eÙ+\2:X2
 
}— e 
Ù
á
Ù
—eÙ}: +j X:j Ù1:X–\+Ù}:+j 
 






 
`vgre` mo ve
 
:
 
`delete` a volu me g rou p
 




 
 
 
Ù:+j1\Ù
 
+}Xe
Ù
á
Ù
e :+Ù}:+j 
`Not` e:
Ù
`af` t er youcreat e t he logic al vo lume s t heyar e t reat ed as no rmal  di sk  so 
`youcana` dd a  f ile syst em t ot hem an d ad d t hem t o 
/et c/f s t ab
 








 
+} \U+–
Ù
á
Ù
 U+–
Ù
:X2Ùj e Ù+:+Ù}:+j 
 
+}\
Ù
á
Ù
\\ Ù+ } U+ ee Ù+\2:X1e2
 
+}X\ ‘
Ù
á
Ù
XÙ+:+Ù}: +jm
ñ

 






 
+}X
á
Ù
X Ù+:+Ù}:+j 
 






 
`lve` xt e nd
:
 
`expand` a log ical v olu me
 





 
`lvre` mo ve
 
:
 
`delete` a log ical volu me
 

:X
 
 
 
 ÙmïtÙ
Ue e X2Ù
sÙ± +
Ù
á
Ù
e :Ù:Ù±+2 ÙeX\:XÙ
± X\e Ù: j X2 Ù

\e X 2
 
 
Ù Ù
 
`I`
 
:
 
`ins` ert  bef ore li ne
 
`A`
 
:
 
`ins` ert  af t er li ne
 
`o`
 
:
 
`add`  new  line af t er cu rrent  line
 
`O`
 
:
 
`add`  new  line bef ore cu rre nt  line   
 
`yy`
 
:
 
`t` o copy  a l ine
 
`p`
 
:
 
`t` o pas t e 
 
`dd`
 
:
 
`To` delet e a li ne
 
`ZZ`
 
:
 
`s` ave and exit
 
`r`
:
 
`s` ave and exit
 
/<
`anyt` hi ng
>
 
:
 
`t` o search  f or somet hi ng
 
(f or w ards )
 
? 
<
`anyt` hi ng
>
 
:
 
`t` o search
 
`f` or somet h ing  (ba ck w ards )
 
 
—je Ù
 
:w
 
:
 
`To` 
`s` ave
 
: q!
 
:
 
`exit` w ithou t  saving  
 
:d
 
:
 
`delete` a line 
 
:
`p`
 
:
 
`pas` t e
 

:
`e`  fi le name
 
:
 
`t` o sw itch to anot he r f ile
 
 
: se t  numbe r
 
:
 
`t` o add  nu mb ered lines
 
:<
 
`li` ne  numbe r
 
>
 
:
 
`t` o ju mp  to a sp ecif icline  
 
:<
 
`fi` rst  li ne
 
>, <
 
`la` st  li ne
 
>d
 
:
 
`t` o delet e a ran g e of  lines  
 
: < 
`fi` rst  li ne
 
>, < 
`la` st  li ne
 
>y
 
:
 
`t` o copy  a rang e of  lines  
 
:
<
 
`fi` rst  li ne
 
>, <
 
`la` st  li ne
 
>
 
`s/` <
 
`o` ld wo rd
 
> /<
 
`ne` w wo rd
 
>
 
:
 
`t` o f ind and repl ace
 
`w` ithin a  
`s` pec if icrang e 
 
:
%s/<
 
`o` ld wo rd
 
>/<
 
`ne` w wo rd
 
>
/< 
`flag`
 
>
:
 
`t` o f ind and 
`rep` lace t hr ou g h the w hole  docu ment
 
 
\ç
 
>ß ß>ß+ ß
÷
ß
++ ß:j XX\ ß:e 2ß>
 
ß>ß+ ß
÷
ß
 :2± X1ßX\å ß>
 
>ß3ß>ßeß +\e ßç\:2
 
 
 Ù2j +e\
 
`Wildc` ard
 
`D` es cript ion
 
[]
 
`L` ist  of  pos s ible valu es
 
`-`
 
`Rang` e of  
`valu` es
 
`.`
 
`Any` s ing le cha ract er
 
*
 
`Any` nu mb er of  ch aract ers
 
^
 
`Beg` inning  of  li ne
 
$
 
`E` nd of  line
 
|
 
`Or` 
 
()
 
`Sub`
`-`
`expres` s ion or slice
 
\
 
`E` s cape charact er
 
 
`fgre` p/gre p 
`-`
`F`
 
:
 
`F` ixed s t ring  searc h 
 
`e` gre p/gre p 
`-`
`E`
 
:
 
`s` earch us ing  reg u lar exp res s ions  
(w ildc ard)
 

`pri` nt f
 
:
 
`f` ormat and pr int  dat a
 
`wc`
 
:
 
`print`  the nu mb er of  lines ,  cha ract ers ,  w ords ,  and t he byt e cou nt .
 
 
`so` rt
:
 
`s` ort  the cont ent  of  a text  f ile
`.`
 
`N` ot e:
Ù
`use` 
`-`
`r`
 
`f` or rever se s ort ing,  
`-`
`k`
 
`t` os pecif yt he co lumnnum ber,  an d 
`-`
`t`
 
`f` or t he delim it er 
 
`cut`
:
 
`ext` ract  sec t ions  f rom 
`t` he provided  
`i` np u t
`.`
 
`Not` e:
Ù
`use` 
`-`
`f` 
 
`t` ospecif yt he colum n/ f ield num ber,  a nd 
`-`
`d`
 
`f` or t he delimit er
 
`di` ff
:
 
`comp` ari ng  f iles  line by line
 
`lo` cat e /fi nd
 

 
`u` s ed t o look  f or f iles
ß
 :e çß
–:jß2ßj\ßW yõ }õ2j++e ß
± 2
ß
e:ßXXe ße X–ß2–ßXX:Xß1\\ \
 
`se` d
 
:
 
`f` or f ilt ering  a nd t rans f ormi ng  text
`.`
 
`Not` e:
 
`most` lyus ed i nsc ript in g and aut omat ion
 
`awk`
 
:
 
`pat` t ern sc an ning ,  manipu lat i ng  dat a,  and g enerat ing  report s .
 
`Not` e:
 
`most` lyu sed insc rip t ing and 
`aut` omat ion
 
1U+\ Ù: Ù
± 2
 

 
±+\– Ùá
 




 

 
±+\–Ùe –U Ùá
 














 

 
 Xe: X\–Ùe –U Ùá
 












 

 
 +\: Ùe\e ÙV–\
á
 













 

 
 +\X X2ÙP OO
á
 










 

 
 +\Ù —je 11
á
 


















 
 







 
 
1U+\ Ù: ÙX UïX U Ù
ñ

 

 
e\Ùee: 2e e XÙ: : ÙUe e X2\á
 


















 

 

Xe
 

 
e\eXe eÙe e X2á
 











 
 

 

 

 

 
e\e ee e X2á
 












 
 

 

 

 

 
e\e e: 2ee e X2
á
 











 

 

 

 
e\ e XÙ: Xe X\
á
 











 

 

 
e\e 2e X
á
 













 

 

 

 

 
e\ e Ù: X: XjXX\Ù: X e X
á
 











 
 

 

 


 

 
ee e X UeÙ
Ù XÙ: \
á
 











 
 

 

 
\X:jU 2Ùe:e 1U+—e e X 2\
á
 









 

 

 
e: X:X – e Ù
ð

á
 















 
 

 

 
e\ e Ue :+Xe X
á
 









 

 

 
 X ÙX\2 Ù
 
eX
Ù
á
Ù
e :e2X
à 2\ Ù
 : Ù1j +e2e :Ù
:2:j e ÙX ÙeÙ
\
 




 
‘ Uïj‘ U
Ù
á
Ù
1U X\\2 :1U X\ Ùj \2Ù‘
 
`.`
 
`Not` e:  commonl yuse d a s it  pro vide s a bal ance bet w een 
`spee` d an d com pre ssion rat ion 
 
—‘
Ù
á
Ù
e :1U X\2 :1U X\ Ùj\ Ù—‘Ùe::+
 
`.`
 
`Not` e:  be st  comp res sionr at iobet w een 
`gz` i p
 
`and` 
`b` z i p2
,  but  is t he 
`slowest`  
 
e:Ue \
 
 
ñ

Ù
áXeÙ2X
 
 
ñ
}
Ù
á\:Ue2+à Ù\:\ ÙUX: X\ ýß
 
ñ

Ù
á –Ùe  ÙeX }ß
 
ñ
—
Ù
á —e X Ùe X:Xß
 
ñ
‘
Ù
áÙ
1U X\2 :1U X\
Ù
j\ Ù
U
 
`.`
 
`Not` e:  end wit h 
`.t` ar .gz
 

ñ

Ù
áÙ
1U X\2 :1U X\
Ù
j \ Ù—‘ß
Ù
`Note`:  end wit h 
`.t` ar .x z
 
ñ
U
á
Ù
UX }\2\
ß
 
ñ
ñ
\
ñ
: X
áÙ
e :Ù' Ùe 2\  Ùe2 :X –Ùj 2e :j
ß
 
ñ
ñ
2:
ñ
\
ñ
: X
á
Ù
+':j Ùe 2 
ß
 
ñ
e
Ù
áe Ùe2ee \ Ù: ÙeXß
 
 ÙjU Ù
 

 








 
 
 
\q
Ù
áÙ
e :Ù\U –Ù: Ù1jeÙe:Ù X
ß
 
: 2}q
áÙ
\–
Ù
e :1UXe Ùe:j X2 ÙeX: XX:X\e+Ù
U–Ùe  2: Ù:e 
ß
Ù
2
: X
ß
2XX:Xß:jX$ j \e :2e 2 j
ß
 
 
:j2e q
áÙ
e :Ù
\ –Ùe jÙ::\ Ùe:ÙU–
ß
 
:ÙXe :Xj \eUÙe 2  ßàe\ Ù‘ Ù–:j+Ù2 Ùe:Ùj2e Ù±X\ e à22
e Ù
:X Ùe:Ùj21:j 2e ÙeXe 2Ù: XÙe ß
 
X
\– 2
 






 
 





















 

 
 U– 2Ù±+\Ù+:++–
Ù
 UX\ X } ÙU X \\ : 2\
áÙ
 










 
 

 
 U– 2Ù±+\Ù
e:ÙX 1: e Ù+:e: 2
áÙ
 













 
 

 
—+ 2Ù±+\
áÙ
 



















 

 
: Ùe\e
Ù
} \++–Ù\e ÙX\– ++ :
áÙ
 

















 
 
 
 
 
 
 


\Ù X:2
 
 
 —áÙ
 




 









 


 







 
X: 2eÙ
ñ
+
Ù
á
Ù
`View`  the cu rre nt  cront ab
 
X: 2eÙ
ñ

Ù
á
Ù
`E` dit
/ creat e
 
`t` he cront ab:
 
X: 2eÙ
ñ
X
Ù
á
Ù
`remove` a  
`cro` nt ab:
 
 
 U Ùe\
 
:j2ßU+—jeß \ Ue\ße \ Xe:X2 ++ßXj 2eße UU X: UXe
 2e\å
ß
 


 
/ et c/ cron. hou rly/
 

 
/ et c/ cron. daily/
 

 
/ et c/ cron. w eek ly/
 

 
/ et c/ cron. mont hly/
 
 
:eÙX:\\ÙX2 
 
 

Ù
á
Ù
 U+–\ Ù\–\e2:X2
 


 





 



 


 
+\1: 
Ù
á
Ù
 U+–\ Ù
e : Ù' 2Ù1: + \
 
1: 2:
á
Ù
 U+–\2:X2
Ù
j eÙ' 2Ù1: +
 



 



 


 


 
 2\1: 
Ù
á
Ù
\e++ÙÙ1: +Ùe '2 +
åß:e çe\ß 2:e ß+ßU2\æe\ßX :112ß e:ßj\ß1UX:
 
X11 : 
á
Ù
X}Ù1: + X:' X2
 
1:UX:
Ù
á
Ù
e2e +
 





 






 





 
\–\e +
Ù
á
Ù
 U+–\ Ù
'2X\
 
 
X\
 
U\j—
Ù
á
Ù
 U+++ÙUX:\Ùee e :Ù:2
Ù
ü Ù\2U\ :e Ùý
 
U\e X Ù
á
Ù
\ : ÙUX:\ ÙeXXe2:\ ÙýÙ
 
UU
Ù
á
Ù
\ : –Ùe 
Ù
e e XeÙUX:\\ Ùj\ ÙüÙ+Xß ß ß ßß ý
 
e: U
ïe: U
Ù
á
Ù
 U+++ÙUX:\Ùee e :ÙeÙ+
 
+\: 
Ù
á
Ù
+e Ù: Ù±+
ß
 
`Not` e:
 
`rememb` er ev eryt hing inLi nux  is a f il e,  soyou canus e it  
`t` o 
`k` now
 
`w` hat  proce ss u ses a part icul ar por
`t` ,  or 
`t` ok now what  process is u sing a pa rt icul ar d irect ory
,  o r t oli s t  opened f il es f or a  pa rt icula r use r
 
`j` o bs
 
:
 
`t` o see w hat  app licat ions  you  pu t  in t he back g rou nd
ß
 
`Not` e:
 
`youcanan` app lic at ionin back g round u sing 
`C` TRL +Z
 
`or` using 
`bg`
 
`comman` d an d t obr ing back  t ot he f oreground youcanu se t he 
%
`+j` ob num b er
 
`or` t he 
`fg`
 
`comman` d
 
`ki` ll
/ki l lal l
 
:
 
`t` o termin at e a pr oces s
 
`pgre` g
 
:
`u` s ed t o g rep t he PID  of  an app licat i o n,
 
`It`  is  the same as  
`ps`  a ux| grep <pro c ess >
 
`ni` ce
:
 
`s` t art  
`an` 
`app` licat ion w ith a 
`cert` ain  
`pri` ority
 






 
`re` ni ce
:
 
`t` o 
`chang` e the priority  of  a proces s  or an  app licat io n.  (al ready  ru nn ing )
 







 

















 
 








 









 
\–\e +
Ù
á
Ù
j \ :2  Ù
 
\–\e 1

ñ
+–‘
á
Ù
X+\:X12e ee Ù:X:eà ÙeX Ù\–\e\à2
} \ Ùj2 +
 
 
\–\ee+Ù:U e\
 
\–\e +Ù\ee j\
Ù
á
Ù
e:
Ù
 Ùe \ee j \
Ù
:Ù\à
 
\ :e 
\ ÙXj 22 à Ù \e :UU Ù:XÙÙ
eeà+:2ÙX:\ \ß
 
 

\–\e +Ù
+
Ù
á
Ù
e:
Ù
2±  j X–\e 

\j e :+e:e ß
 
 
\–\e +Ù
 \+
Ù
á
Ù
e:
Ù
UXe
Ù

\ 
Ù
 X: 1Ù\eXe
Ù
j e :+e:e
ß
 
`Not` e:
 
`insome`  case s,  
`evenif`  youd isa ble a se rvic e som e ot her s ervic e mi ght  t rigge r t his se rvic e t ost art  and it  will st art  ag ain,  so if  youw ant  
`t` o 
`prevent`  f rom load ing ev enif  ot her s ervi ces dep end on it  use  
`s` y s t em ct l m as k.
 
\–\e +Ù
\eXe
Ù
á
Ù
e:
Ù
\eXe
Ù

\ 
 e
ß
 
 
\–\e +Ù
\e: U
Ù
á
Ù
e:
Ù
\e :U
Ù

\ 
e2
ß
 
 
\–\e +Ù
X\eXe
Ù
á
Ù
e:
Ù
X
eXe Ù

Ù
\à Ùj\ j +Ù:XÙUU +2±  j Xe22  Ù:XÙ
X X\  Ùeß
 
\–\e +Ù
X: :e ïU: X: ¯
Ù
á
Ù
e:
Ù
\–ÙX:e Ù:XÙ\j e 2Ùe–\e 
ß
 
 
\–\e +Ù
+ \e
ñ
 e
ñ
±+\
Ù
á
Ù
+ \e \++Ùe2 \e++ 2 +
 
\–\e 
ñ
–‘ Ù:U e\
 
\–\e 
ñ
+–‘ Ùe 
Ù
á
Ù
 U+–Ùe Ù: X $:XÙ \e Ùe ::e ÙUX:\
 
\–\e 
ñ
+–‘+
Ù
á
Ù
+e \++Ùe –\e ÙeeeXe Ù\:Xe–Ùe  e 
e  ::' Ùe:2+ß
 
`Not` e:
 
`usef` ul f or i dent if ying wh ichse rvice s ar e s lowing down t he boot  p roce ss
 
\–\e 
ñ
+–‘ Ù
U+: e
Ù
á
Ù
e2 X e\j+ ‘ Ùe:e ÙUX:\à Ù\: Ù
 Ù\ XeXe2 : Ù+:2e Ùe::' ß
 
`Not` e:
 
`redi` rect  t he out put  t oa 
`.s` v g 
`f` ile an d t henyouc anview  
`t` he out put  inany br owser o r 
`im` age v iew er
 
\–\e 
ñ
+–‘ Ù
\jX e –
Ù
á
Ù
e :\\\ Ùe}++Ù\ X Ù: Ùe Ù
 
 Ù :2 ±j2
 
+\j\
Ù
á
Ù
+ \e22 \ 
 
 
+\U
á
Ù
+ \e Ù
 \2Ùe–\e 222 :Ùe
 
\
Ù
á
Ù
 U+–Ùe :\2Ùe Ù
' 2
Ù
X 2 Ù
ß
 
:
Ù
á
Ù
X XXXe:X22Ù jÙX :X
 
e:X' 
 
21+
Ù
á
Ù
2e X:++ Ùe:X' 2 Ù X:
 
U Xï : 2±
Ù
á
Ù
\ : X\ Ù
2±  j Xe2ß
Ù
 
 UÙX:je ïX:je
Ù
á
Ù
e :Ù\:j Xj +e Ùe–ß
 
2\+: : 'jU
Ù
á
Ù
e :Ù ÙeUÙ:Xe +X1Ù
21ß
 
 2e
Ù
á
Ù
e j X2Ù:2Ùe Ù
\ß
Ù
 

e X X:je ïe X Ue 
Ù
á
Ù
e X :U\ ÙüX:je\ ýÙÙ–:j2Ù\U X\ Ù+'
ß :: +ß1
 
\\
Ù
á
Ù
\\2Ù \eeeß
 
`Not` e:  e. g.
 
`ss`  
`-`
`a`
`n`,
 
`t` odisplay  all ses sionan d d isa ble  name look up.
 
`ho` st name ct l se t
`-`
`ho` st name  <ne wn ame >
 
:
`t` o chang e you r c omp u t er name 
 
e + e
Ù
á
Ù
Xe222ÙüÙ2:e Ù\ XÙ
 
\\
Ù
á
Ù
\ Xe222
 

Ù
á22 Ù:2Ù
\ ÙU:Xe
 




 
 
:Ùe: Ùj Ù2 +
 
 +– 2—
 






 
PßÙ: X'Ù : X1 :2
 

 
`Status` of Ne twor k M anage r  (
`Di` spl ays th e  status of the  Ne twor k M anage r  
`se` r vi c e
)
:
 

 
 
Q
ßÙ 
 e
 

 
e++ e: X'}\á
 

 

 
}U
ï
á
 




 

 
 :}2: Xe: 2á
 



 
 
R
ßÙ
: 2 2 e: 2 e
 

 
e++ 22e : 2\Ùüe}e } ýá
 




 

 
ee } 22e: 2\á
 







 

 
 
ñ
 22e:\\: Xýá
 












 

 
 +: 22e: 2\á
 




 
 
S
ßÙ

ñ
 Ù
 U: 1 1\
 

 
2Ù: X
ñ
 e: X'\á
 

 

 
e} ++ 
ñ
e: X'\á
 


 

 
 22e Ùe:
ñ
e: X'Ùü\\: Xýá
 









 
 
T
ßÙ: 1 1\Ù 2 e:
 
 




 
 +U
á
 
 Ù 2ÙeX
 
UX 2e
á
 
++Ù\ e\ Ù:XÙe 222
 
 

 
 eÙ\eeá
 






 

 
 eÙe– á
 







 

 
 e 
 







 

 
 e}S e :Ùe:+á
 




 

 
} Ùe2\— e á
 


 

 
 e:X' Ù+
Ù
ü Ù+Ùý
 
 X + + ßj e : X + ß
 
e e U\ á ï ï–:je j ßï $ XVæ \: ++}—‘
Ù
 
 

 
'Ùe Ù\ee j\Ù: Ù±X++
á
 





 

 
e} ++ Ù‘:\
á
 







 

 
: Ù\e Ùej+e Ù‘: 
á
 










 

 
ee } Ù‘:\ e 2e X\e eÙe: Ùe 1
á
 










 

 
e} ++ Ù‘:\
á
 







 

 
:Xe: 
á
 









 






 

 
: ÙX +:Ùe Ù±X++
á
 





 

 
:2 Ùe Ù‘: 2 Ù:  2e X
á
 














 








 

 
e++Ù\jUU: XeÙ\ X }\
á
 








 

 
:++:Ù\ X }Ù\ UÙ‘: 
á
 















 
 



 







 

 
:++:ÙU: XeÙ \UÙ‘: 
á
 














 
 

 
 















 
 

 
e++:Ù\ X }\Ù \UÙ‘: 
á
 










 
 




 

 
e++:ÙU: Xe\ ÙÙ\UÙ‘: 
á
 










 
 





 

 
eUU+ÙXj+ \Ù \UÙ‘: á
 











 

 
 \U+–Ùe+ÙU Ù: XÙXÙ+ Ù: Xe
á
 


 
 
 

 
 
–Ù
 
 2X – Ue Ù\Ù
 
Ù
+j'\
 

Ù
Ù: :e :Ùj\X : 'j Xe Ùej \e\ Ù2:
e
Ù
X}
Ù
2 X–Ù
 
 









 
 
2X–Ue:2Ùj\2Ù+j'\
 

 




 
e +Ù:X \2 X –U e' à Ù\:' \j X:j ÙjU Ù–:j Xe2 e\ Ù
+–\Ù ::e :Ùj21:j 2e Ùe Xß
 

 







 
e +eUUe X –Ù:XÙe 2 – Ue ' Ùj\ Ùe:j\\ 2
áÙ
ï ïï1– ö –U e:+
ß Ù–:j+ + \:Ùj\e Ùe:Ù :e +j 2:j –U e 
 

 




 
 

 








 
:X  –U e 'Ù±+–\e Ù–:j X:2j 2ee ß Ù
 

 



 

 

 
 eÙ–:jX2\e Ùj21:j 2ee2 +:\e Ùj\ Ùe}112 Ù: X Ù–: j Ù
\ j e 2Ùe–\ee+j e :+–Ùj21:j 2ee2:\
 
e:: +
 

e::+ ß:X ß1:2 e:X 2 ß2X 2 ß\–\ee\ ß:Xß \jX e21U + 2ßUjXU: \åe++:\ ß
 2 \eXe:X\ ße:ßeX\ ße:ß± +æß1:2 e:Xß\–\e++\2eß
\ j\j\ :Xße ß
\–\e
 
– 1U: 2e\Ù:  e
 

 
 e
áÙj2\ ÙX U:2\:X Xje \ Ùe:Ùe : ß
 

 
 e ÙXj+\
á X Xj + Ùee 2 e \XUe j Xß  ß à Ù\–\e+\à Ù
± +\àß ýß
Ù
ß
 
`Not` e:
 
`usually` st ored in 
/ et c/ aud i t / aud i t .r ul es
 

 
 e Ù+: \
á:\ Ù 2ejX+–Ù:j 22Ùïï+ : ïj ïj ß+: ß
 

 









 
éÙÙ
ñ

Ù
áeÙeï\
 
éÙÙ
ñ
U
Ù
á:2 X X2e e X e2ß
 
éÙÙ
ñ
'
Ù
áÙ' :Ùe –Ùe j ÙXj +ß
 
 
 ee +Ù
ñ
+
Ù
á
Ù
+ \ej ÙXj +
 
j\XÙ
ñ
'
Ù
á
Ù
 Ùe:\ Ù:Ù\U +
 
 Ù\\Ù'–\
 
 e\ ßX::ßXee \\ ß' –\Xße± X\e :ej \ 2 ße± X \e: eß: ß
\–\e e eß2:eß :j 2eX: U–X 212\ ße:ß 2eß \eX:2 ß'\: ße ß ' ++ß
+\ ß\jX2
åe ßej+e ß:X 
÷
 \eX:\
 
Pß
 
eÙï\\ 2 \ Ù' Ù
 
Qß
 
e Ùj\ Ù
\\ 
ñ
'ß 'j X:je++Ù: Ùe2 \ 
± +\ Ùej \ Ù'
 








 
Rß
 
Ù–:jX\  e Ùeà ÙXeXe Ùe\ 2Ùü\\ 
 
j—
 
jX e –
÷
 22 2j —ß 2j —ß \X eX eejX: X 2j —ß\–\e ßee2:X\\ ß
2eX:+ßU :+ 
ß
e:ß:2ß : ßUX:\\2\\2e eß± +\2e ß
UX:\\
æß\: \2ß e :2+ß +ß:ß \jX e –
 
 
 2: X:
áj —ÙU:+\:X à2+e2\X: 2: 
 
 X \\ }:
áj —ÙU:+\ Ù2:e :X àe:+e2\X:  eÙ
j \:XÙeX:j::e ß
 
 \+ 
áj —\ Ùej X2 ¯Ùe–ß
 
 

 

 
112+Ù Ù–:j2 :X2Ùj ej —à Ù:X+Ù:j Ù:2 +–Ùe  
 XXe Ù1:à ee j \+Ù:j Ù1:X2:X2 Ù\j XXe Ù1:2 1:
2±  j X2±  Ù±+ß ß ß ß ßß ß ß ß
 
`Not` e:  t osee t he log f iles gene rat ed byS ELinux ,  youcan  navi gat e t o 
/ v ar / l og/ aud i t / audi t .l og
 




 
 :XX 2 2j —à Ù–:j2Ùj\ j2 \e Ùe:Xß\\ ÙOÙ
2:X\ ÙP
 
 



 
e :Ù\j —
Ù
2e—e Ù : Ùe2Ùe \X :X –Ù
 
 

 
 U+–ÙUX:\Ùej —2ee
 
 







 
\ : U:XX22e—e Ù :Ù±+
 
 





 
e +ÙXeÙ±+e \j +e2e—e à Ù\:2 2 2+Ù: Ù
 
 







 
 
:22ee2 'e Ù
\e
j \}11 2+ 2
j +e2e—e à Ù\: eÙXj 22 2 Ùe112 ÙXj 2ÙXe :X2Ù:2 Ùe +  2e Ù
e :Ùe2e—e ß
 
 









 
e :ÙU:Xe Ùe:Ùe++:Xe \ Ù:XÙ e e Ù
 
 
 UU X1:X
 
XÙe:j —à UU X1:j XX:2 :X\2e X:+ß2+ ' 2j — Ùj\ Ù
\j \ Ùüß  ß ÙUX:\ ýÙ2 \ Ùüß  ß Ù± +à ÙU:Xe àX UU X1:j X1U +e \Ù
UX:± +
ñ

Ù
UU X:
Ù
ü1:X
ñ
 X
Ù
  –ÙUU +e2ÙUX:e UU X1:j XÙ\ÙUX:± +à Ù
 \Ù±+
 

 2: X:
á2Ùeà UU X1:X 2:X Ùej + 2Ùe:± +ß 22Ùee Ù
+e Ùe ++2:  
 
 1U+ X \\ } ýÙ
á2Ùeà:+e2\X:  e Ù2:e: ' \\ Ùj\j +Ù:XÙ
 j  2: Ù2 ÙUX:± +ß
 
 




 
 U+–Ùe  XXe Ù\eej \à Ù+: ÙUX:± +à Ù2 e Ù1: X e2ß Ù
 
 



 
+e ÙUX:\ ÙXj 22:j e UU X1:XÙUX:± +
 
 



 
:ÙeÙ2 ÙUX:± +:XÙ2UU +e2 à Ù:2:j ÙXj 2Ùe112e Ù\e Xe Ù1:2 X Ù
e UU +e2 Ùe:Ùe:± +ß Ù
 
 




 
j \ :ÙjU—e ÙUX:± +ß2:j ÙX j 2Ùe112e+ 2+‘– Ùe:\ Ù
e :± +\2 :1U + Ù1:2 +U\ Ù–:j–Ù\j  e 2 \ Ùe:Ù
e XX U:2 ÙUX:± +
 
 



 
ÙWj à2+2UX:± +e2+ ÙeUU +e2à2e+ 2+j 
e \2Ù: XÙ2\X \ßÙ:: \eXe ÙU: 2e à2
e2e Ùe:Ù: Ù
e X:j  Ùe:\ Ù: Ù

ñ
 2UX: 
Ù
e–ß Ù
 
 



 
Uj eÙUX:± +2e ::X Ù1:
 
 



 
Uj eÙUX:± +2e :1U +Ù1:
 
 





 

ÙUX:± +ß
 
 






 
X} Ùj2' 2: 2ïj 2j \ UU X1:XÙUX:± +ß
 
 
Ù
 
 
 
2 \e+ Ù e
 
Ue
Ù
á
Ù
j \ :Ù
 
Ù
:22
ñ
e X:\
`.`
 
`Not` e:
 
`it`  combines t he f unct ional it yof  apt
`-`
`get`  and apt
`-`
`cache`
 
`yum/dnf`
 
á
Ù
e 2 XÙ: XÙXe
ñ
e X:\ß
ß
:eç
Ù
–j 1\2 ß Xj++ –ßXU + –ß2æ ß\:ß2 \ß
eßje jX
 
XU1
Ù
á
Ù
Xe2à Ùe\ Ùe Ù: +2 Ùee ÙXe
ñ
 \ X:Ùj\ :Ù
j \
ß
ß
:e ç
Ù
–:j
ß
\:j+2 e ßj\e
ß
\e ß\ß2ßX U+–ß –j1õ2
æ ßXe \ß\e++ß j\ß e:ß1 U:Xeß'–ß
 
 
eÙ: Ue \
 
Ue Ù+ \e
Ù
á
Ù
j \ :Ù+eß
 
`Not` e:  used if  you  k now what  youare look in g f or
 
 
Ue Ù
\X
Ù
á
Ù
j \ :Ù\XÙ:X:Xß
 
:eç ßj\ ß–:jß:2e ß'e ß–:jßXß+ ::'2ß
`f` or
, 
`s` o  yo u  can  pro vide  ake ywo rd,  andit wil l  se arc h  in  th e  pac kag e s  andthe
`ir`
 
`de` s c riptio n  for a match
 
Ue Ù
 2\e++
Ù
á
Ù
j \ :2 \e++
ß
 
`apt`
`-`
`ke` y add
 
:
 
`t` o add  a key  or a has h,  so  it  c an beu s ed t o verif y pack ag es
`.`
 
`apt`  updat e
 
:
 
`t` o up dat e the apt  cache
`.`
 
 
`apt`  
`upgra` de
 
:
 
`t` o up g rade t he sof t w are pack ag es  ins t alled
`.`
 
`apt`  
`full`
`-`
`upg` rade  
:
`u` pg rade pack ag es  and 
`in` s t all new  pack ag es  or rem ov
`e`
 
`exist` ing  o nes  as  
`need` ed
`.`
 
`apt`  re mo ve
 
:
 
`t` o remove/ u nins t all a sof t w ar e
`.`
 
`apt`  
je: X 1:}
Ù
:
 
} Ù+X2
 ÙeeX:Ù+ :2 XÙX
ß
 
`apt`  
`cle` an 
:
 
`Clea` rs  the AP T cac he
`.`
 
`apt`  
`aut` o cle an 
:
 
`Cleans`  up  part ia lly dow nl o aded  pack ag es
`.`
 

 
– j1ï2 Ù: Ue 2\
Ù
 
–j1Ù+ \e
á
Ù
e :Ù+e+Ù\:X
ß
 
–j1Ù\X
Ù
á
Ù
e :Ù\X2ÙX\ Ù:X Ù ':X
ß
 
– 2:
á
Ù
e :Ù\2:X2j e 
ß
 
– 2\e++Ù
á
Ù
e :2 \e++
ß
 
–j1Ù
X 1:}
Ù
á
Ù
`t` o remove/ u nins t all a s of t w are
`.`
 
2
Ù
je: X 1:}
Ù
á
Ù
+::' Ù:X2–Ùj 2j \2}
ß
 
–j1Ù
jUe
Ù
á
Ù
 
`t` o up dat e the cache,  ins t al l t he up dat es ,  and u pg rade t he OS
ß
 
`Not` e:  unlik e a pt  
`w` here youhav e t hree dif f erent  comman ds;  one  f or up dat ing  t he cache,  one f or inst al ling  t he upd at es,  and  one f or u pgr a ding 
`t` he dist ro,  
`y` um  up d at e
 
`combin` es t he t hree  inone comman d
 
–j1Ù
UX:}\Ùê ï—– \
Ù
á
Ù
e :Ù±2  Ù2:Ù —
 
 
XU1
Ù
ññ
 1U: Xe Ù
á
Ù
`t` o add  a key  or a has h,  so it  can beu s ed t o verif y pack ag es
`.`
 
 
 

 

 
2\e++Ù e áÙ
 




 

 

 
\} Ù e: 2±jXe: 2Ù: 2Ùe Ù\–\e 1Ù+}+á
 





 

 
\} Ù e: 2±jXe: 2Ù: XÙj\ Xá
 






 

 

 
\} Ù e: 2±jXe: 2Ù$ j\e Ù: XÙe ÙUX: $e á
 






 




 

 
\: 2±jXe :à +
àÙ
e Ùe— e e: XÙ–:jÙ2e Ùe: Ùj\
Ù
e jX2Ù: 2Ù
: +: X\
ýá
 






 







 






 






 
 





 

 
+ \e: 2±jXe : 2áÙ
 
 






 

 
 e+ ‘ Xe: X –Ùe: Ùe X'–Ù e á
 




 





 

 
'Ù e Ù\ee j\
Ù
Ù±+\X 2
e 2Ùe X'à2–Ù\} 2Ù
 ý
á
 




 

 
\eXe Ùe X'Ù± +
Ù
üUj\Ùe: Ù\e ÙXý
á
 



 


















 
 




 
 


 



 

 
 
 
 
 

 
 11 e2\
Ù
üUj\Ùe: ÙX U:\ e: X –ý
á
 






 
 





 
 










 
 



 
 






 
 

 
 Ù–:jX: 11 e\á
 



 

 
'e\} á
 



 
 






 

 
 ++'Ùe: Ùe Ù+\e Ù\} ÙU: 2e á
 



 

 
j\Ù+:+ÙX U:\ e: X –Ù e:ÙX 1: e ÙX U:\ e: X –Ùá
 


 



 





 
 





 
 








 

 

 
 +:ï+:ÙX 1: e ÙX U:\ e: X –ÙÙá
 


 
 

 
eX
 


 

 
eXeX\á
 


 
 

 
 eÙe:2: e XX
 


 

 
 XX\á
 



 
–Ù+ 2 Ù
 
 : e: U
Ù
áÙ
e :Ù\ïÙ
 
 
 
ß:Xße eXe Xß\ X ßeeßXj 2\ße X:j22 :++e\X:X12ß
2
+:\
ß
 eæß\:ße ß–: j2ß : 2 eß+eåeß eX\ X– \õ 2 :X'ß
õ
 

 
 2\e++
 




 

 
Ù
+ 
á
 

 


 

 

 
2 Ù:  ej2á
 


 

 
 \U+–: ++eÙU X: XeÙá
 


 


 


 


 


 
 

