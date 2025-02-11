java c
Monthly Assignment 2 
LINC12 Fall   2024 
October   25,   2024 
Assignment due: Sunday November 3, 23:59 on Quercus 
Total points: 45 
The following   exercises must be   completed by uploading   a   PDF   document   onto   Quercus.    This   assign-   ment   covers   material   through   the   Thursday, October   17   lecture.
This   assignment   is   worth   45 points   altogether.   It   contains   a   variety   of   questions   ranging   from   simple   to difficult.   It also includes problems that were presented as practice exercises.   Refer to your notes from lecture   for   information   on   how   to   complete   those   problems.If   you   work   with   anyone   else, or   discuss   answers   with   your   classmates, please   indicate   their   names   some-   where   on   your   returned   answer   document.      This   is   so   we   know   to   expect   similar   answers.      However,   you should hand in your   own unique work!
1                                    Predicate   Logic   (5   pts)
Translate   the   following   sentences   into   Predicate   logic.    You   do   not   need   to   provide   a   model   or   a   legend   for constants   in   this   question.
(1)            Robert   likes   Pia   and   Georgina.
(2)            Dr.   Tannhaus   resigned   or   disappeared.
(3)            Pilar   gave   Beng   Beng   to   Qin   Xue
(4)            Gregor   is   sick   and   asleep.
(5)          If   Dr.   Tannhaus   resigned,   Bronwyn   will   be   happy.
2                                 Set   Theory   (6   pts)
Recall De Morgan’s laws from our work in Propositional   Logic:
(¬p ∨   ¬q)   ↔   ¬(p   Λ   q)
(¬p Λ   ¬q)   ↔   ¬(p   ∨   q)
It is possible to apply De Morgan’s laws   to   the   relationship   between   two   sets   as   well.   Rewrite   De   Morgan’s   laws   using   our   set   operators.
3                               Writing   a   Model   and   representing   Propositions   (20   pts)Below   is   a   short   passage   with   several   sentences.   Create   a   model   populated   with   the   named   individuals,   and with   definitions   of   all   of   the   predicates   used   below.    Remember   to   name   the   model,   create   a   universe   with all   of the   relevant   individuals,   and   create   definitions   of   both   definite   descriptors   as   well   as   the   predicates themselves.    Use   correct   Set   notation   to   do   these   definitions.    Ignore   things   like   tense,   conjunctions   etc.    in the   passage;   focus   on   creating   a   model   that   is   suf代 写LINC12 Fall 2024 Monthly Assignment 2Processing
代做程序编程语言ficient   to   determine   the   meaning   of the   sentences   in   this   passage.
(6)          Robin   introduced   June   to   Nico.    Robin   and   June   are   people,   but   Nico   is   a   fish.    Gregor   owns   Nico,   but Gregor is   sick.    Olivia   also   owns Nico,   and   Olivia is   also   sick.    Robin   and June   are helping   Gregor   and   Olivia.   June and Robin will feed Nico.
4                                  Evaluating   Truth   of   statements   relative   to   a   model   (14   pts)Below   I   will   provide   you   with   a   Model, M1.   The   following   questions   will   give   you   several   statements, written in   either plain English,   or in the   syntax   of Predicate   Logic.    You   should   determine whether these   statement   are   true   in   the   given   model, and   say   very   briefly   (one   or   two   sentences)   how   you   know,   or   where   you   looked to   determine   this.
•    U = {Hao   Xuan   ,   Kaz   , Virgilio   , Arshi   ,   Qin   Xue   ,   Beng   Beng   ,   Osito}
•      [ hIM1      = Hao   Xuan;   [   kIM1      = Kaz;   [   v   IM1      = Virgilio;   [ a   IM1      = Arshi;   [ qIM1      = Qin   Xue;   [   bIM1      = Beng Beng;   [ o   IM1    =   Osito
•      [ DOG   IM1    =   {Beng   Beng}
•      [ CAT   IM1    =   {Osito}
•      [ PET   IM1    =   {Osito, Beng   Beng}
•      [ PERSON IM1    = {Hao Xuan, Kaz, Virgilio, Arshi, Qin Xue}
•      [ HAPPY IM1    = {Beng Beng, Osito,   Qin Xue, Hao Xuan}
•      [ PHD.STUDENT IM1      = {Kaz , Virgilio , Arshi}
•      [ OWN   IM1    =   {〈Hao   Xuan, Osito〉   , 〈Qin   Xue, Beng   Beng〉}
•      [   LIKE   IM1      =   {〈Osito   ,   Hao   Xuan〉 ,   〈Hao   Xuan   ,   Osito〉 ,   〈Virgilio   ,   Osito〉 ,   〈Kaz   ,   Osito〉 ,   〈Arshi   ,      Osito〉   , 〈Hao   Xuan   , Beng   Beng〉   , 〈Qin   Xue   , Beng   Beng〉   , 〈Beng   Beng   ,   Qin   Xue〉   , 〈Beng   Beng   ,   Kaz〉
, 〈Beng   Beng   ,   Hao   Xuan〉 }
4.1                     Q1
{x :   (x   ∈ [DOG]M1) V (x   ∈ [CAT]M1)}   ∈ [HAPPY]M1
4.2                     Q2
|{y :   LIKE(o,y) in   M1}|   >   1
4.3                     Q3
If   someone   owns   a   pet,   they   are   happy.
4.4                     Q4
[PHD.STUDENT]M1 ∈/ [HAPPY]M1
4.5                     Q5
Virgilio likes every pet.
4.6                     Q6
[PHD.STUDENT]M1    ≤   {x :   LIKE(x,o) in M1}
4.7                     Q7
Beng Beng likes the owner of   Osito, but Osito   does   not   like   the   owner   of   Beng   Beng.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
