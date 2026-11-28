# M433 Peak Program Meter · Meter

Ward-Beck Systems M433, 1992|25. Wiki page: [M433 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M433.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 13 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 3 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 134 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 7 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 22 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1992 - M433 - 434 - P002 - 1-1.jpg](MANUALS/1992%20-%20M433%20-%20434%20-%20P002%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** | +8, +14 dBu (ref. 600 ohm source). 0,+4, +8,+14 dBu (ref. 150 ohm source). Strapable to within +/-0.25 dB between steps |
| **Frequency response** | +/-0.3 dB from 30 Hz to 15 kHz: |
| **Noise** | 40 dB below reference ('4' on BBC scale, Meter Scale [) |
| **Source impedance** | 600 ohms or 450 ohms_ balanced /unbalanced |
| **Input impedance** | Greater than 2SK. |
| **Maximum input** | +24 dBu. |
| **Attack time** | (measured at kHz). Burst Duration (msec) Steady State 100 Instrument Reading (in dB relative to mark 6') +/-0.5 dB 25+/0.5 dB +/-0.75 dB -9 +/-1.0 dB |
| **Delay time** | 2.5 [0 3.2 seconds from mark 7' to mark (measured at kHz). |
| **Power requirements** | +24 to 28 volts regulated or unregulated: 22 mA nominal. 100 mA nominal if LED illumination |
| **Ambient temperature** | Dimensions: to 50 degrees Celsius M434 4.5&quot; wide 2.9&quot; high 2.75&quot; deep_ (114 mm 74 mm X 70 mm) M433 4,0&quot; widc 2.7&quot; high 2.75' dcep (102 mm x 69 mm x 70 mm) SA14-060 (Amplifier card only) 4.0&quot; wide 2.6&quot; high x 0.6&quot; deep: (102 mm * 66 mm x 5 mm) |
| **Weight** | M434 M433 SAI4-060 0.7 Ib. (320g). 0.66 Ib. (300g). (Amplifier card only) 0.1 Ib. (41g). |

## Circuit description

From [1992 - M433 - 434 - Peak Program Meter (2).pdf](MANUALS/1992%20-%20M433%20-%20434%20-%20Peak%20Program%20Meter%20(2).pdf) pages 10-15 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**&quot;1433 /&quot;1 434 PEAK PROGRAM METER**

(Re fe.. to schem...tlc 614_060_02_001)

The incoming b era n ce c audios i g n a l is e u e e vet e e by II loss n., l work consist ing o f R3,R 4 and shun I..esta te.. s Fl6 Ih rough R12. The shun l loss r e SiS lO&quot; iss elected b y sens i lill i t y Sl.....p sW l, This St&quot;ll P de te..mi n e s th., signal le &quot;,,1 &quot; p plied top..e&quot; mp lif le r Ul_A &quot; n d l h.,...... fo..e c lll ib&quot;&quot; les th., &quot; mp l ifie.. for &quot; &quot;.. to us input op e&quot;&quot;ling I.,,, e ls &quot; n d Impeda n c.,s. P..ec is ion..e sis lo&quot; s R6 to R12, ins e.. res with s Wl, p..o &quot; ide th., shunt leg of this n etwo.. k. tn ese...,sIS to.. S we..., se lec t., d 10 produce... sig n&quot; i a tl enu &quot;tion w l lh in +/ _ 0.2 5 d B of these lec led sen sit ill il y.

The sign,, 1 which i s...mpli f ied and b uffe...,d b y U I-A i sled to a p..ecislo n full wa&quot;e..ec tlfle.. ci r&lt;:u il. This..ec tl lie.. c r..cult conSistS of U2 &quot; n d Its a SSOCI&quot; ted corn ponen t s.

The..e s ul ting p..ecrstcn..ec t ifi e d lIoll ag., d.. i lle s &quot; b..e a k -po int amp li_ fie.. Ul _B I/ ia l h., Ih..es hold cont..ol R22. The g... in oft his e mplifl e.. is &quot;..... ied such as 10 &quot; p pro x ima tea log..... ithm icc onl/ e.. s ion of l h e.. ec t lfi e d l/ol l&quot; g e. This is a c hie &quot;ed b y h &quot;' lI lng the ll mp li fie &quot; g&quot;in IIll &quot;y &quot; cco.. ding t o l hell mp l i lu de oft hell p plied inp ul s)g n ll l lIo l t &quot; ge. B..e...k l r-a n s i,a o.. s 01 10 06 e Ion g w i l h the i....e spec li&quot;e.,mi lle.. &quot; n d col lec to.....,s is to.. s ll &quot;e s wit c h., d shunts &quot; c.. o s s th., r e eee ecx.. e siS lo.. R36. T.. i m cc n t..ol s R23 10 R28 (SET 2 10 SET 7) independ.,n t ly se l Ih e l u.. n -on lIo lt...g e fo.. e&quot; c h o f these b..e&quot;k t..a ns iS lO&quot; S.

The OUlpU I o f UlB i s buff e..e d b y U3_A. The ll llll Ck and dec...y ch&quot;..e e te.. l s tlc soft h e PPM mel e....... e e et e..m in ed bye et etc..c ap aci lo.. n e lw or k R51, R54, C4 lliong with l h e mere.. ball i slic s. These e e..a mt!!le.. s &quot;..e s e l fO&quot; lh in St&quot; nd&quot; r d *Bs4297 end eBe De&quot; elopmen l Re po.. t,+'6 0 4 1.

U3_B p..o&quot; ides theme te rd.. i&quot;., Cu.... en l l hro ugh c u....e n l s o u r-ce &quot; e sI SIO&quot; R56. This o u l Put appe &quot;......1 lh e)n leg..,, 1 mete rmounl lng p &quot;d &quot; n d &quot; t co nnec lO.. pin 3. Th., con nec to.. terminal Se&quot;&quot;e&quot; &quot;&quot; the mel e&quot; con nec l - Ion point when II Is n ec e s s e..y 10 &quot;emO le Ih e PPM mete.. f..om the

s A14-060 &quot; m p ll fie &quot; llssembly.

p s.

WAR DB!! CK eVe T!!&quot;,..e LTD,

M433 jM434 PEAK PROGRAM METER

The SA14_06 0 requires 24 to 35V DC. This voltage 15 r egu l&quot; ted down to +22V DC by regu l&quot; tor U4. Resistors R57 10 R59 5101 U4' s out pul volt &quot;ge while c&quot;paci tors C5 and C6 provide powers u p ply decou p l ing. Diode CR7 protects against Inadvertent voltage rev e r sal, while U4 cont&quot;l n sin te gr,,1 cir&lt;:ui l ry 10 protect &quot; g &quot; ins t short circuits &quot;nd ove rvo l t&quot;ge. The half voltage point forth e 5A14-060 is 5101 b)/ decouplin g l r &quot; n s ist o r 08.

p s.

**SET_UP PROCEOURE**

The M433/M434 PPM' s are factory calibrated and normally d o not r e quire r ec al lbr at lon. These n s il i v it y strap SWI a c com mo dates input It ·vel s o f 0, +4, +8 and +14 dem fore i the r-600 o r-150 ohm Impedance s within +/_ 0.25 dB of these lec ted value. If i t becomes n ec e nary to r-e -cal lb rate the PPM, follow the procedure below,

Note: This procedure is b a 5t!d upon a sensitivity switCh. selling of a dBm, 600 ohms. If a different setting Is used to calibrate theme te r, substitute thea p prop ria te levels.

Strap SWI to the 0 dBm 600 ohm position and ensure that all trim controls are S&lt;'!t lull CCW. Ensure that the mechanical zero oft h e meter i5 set properly.

Apply a 1 kHz signal a t -12 demo Terminate input with 6 00 ohms.

Adj u 51 threshold control R22 tod eflect the meter to the -12 d B mark (' 1 ' o n BBC scale 1_1). The range oft his control should be app r o &quot; ima te ly +/ -3 d B.

Increase the input level b y 4 dB to _8 dBm. Turn set 2 control R23 CW un ti I theme tern e.. d le moves to th.. -8 dBm mark on the see te (' 2 ' o n BBC scale).

te ee e se input level by another 4 d B to _4 dBm. Turn Set 3 control R24 CW setting the needle to the _4 dBm mark on theme te r scale (' 3 ' o n eBC scale). Confirm linear i t y bye uen vet ing signal i n 1 d B steps to _8 dBm, meters h o u ld tracks igna l.

Inc r ease input level to 0 demo Adjust Set 4 control R25 CW to set theme tern ee dl eon thea dBm mark on the meter scale !conf irm lin..a r i ty a sin 5).

Increase Input level to +4 dBm. Adjust Set 5 control R26 CW to set theme t.. r needle on the +4 dBm mark on theme te r scale (con firm line ar-it y a sin 5).

Increase input level to · 8 dBm. Adjust Set 6 control R21 CW to

set theme te r nud leon the +8 dem mark On theme ter scale

(confi rm linear it y as i n 5).

**1014]]/101434 PEAK PROGRAM METER**

Incr........ input level 10.12 dBm. Adjust Sel 7 COIHI&quot;OI R28 CW 10 se l the mele&lt;&quot; needle on Ihe +12 dBm ma..k on Ih e meier scale. In cr........ level b r 2 dB. Mel... n_d le should be.1 end.... Nt e... Conf l..m l inea.. itr 0 ' lhe see te b r &quot; tten.... ting sl g n.1 In 1 d B Slegs 11'I1&quot;OU91'1 f...11 se. l. down to _ 16 dBm. Mel et'&quot; needl. should.. _en Ihe ' off' ma rite.. e t -16 dBm +/ -1 d B. Sililn. l s below Ih isle vel s l'lo...ld nol ca us. e deflect ion oft t-e mele...

p s.

M 4 U/M4 J4 PEAK PROGRAM METER

PARI PE SCRIPT ION MFG MEG PARI NUMBER

PPM Aml'&gt;lifi er

MeIer Movemenl f o.M433 (4&quot;) Bach. 523WL fo. M434 (4.5) Simpson 524WL

Extension Cable (4 r t.) Mini Latch Housi nB Be~B 65SJ7-o 10 Mini PV Terminals PY'·47712

SAM·OliO rPM AMPlifiER ASSUIR I Y

C' C:l.l'&gt; a;i lo r 10 uf /3 5 Y Kemet T390Cl06M035AS C2 IOu F/35 Y C3 lO uF/3 5 Y C&lt; SOT (.9 10.97 uF /35 V) T3 90Bl OSM035AS CS 10 uF / 35 v T3 90CI 06 M03M S C. IOu F/ 35 V T390C I06 M03M S CJ 47 uF /16 V Rub yeon IOu F/35 V C' 22 pF Philips 2222·63t·5 B229 C, 150pF 2222·63S ·70 1S1 C R I 10 C R6 Diode Fail eh ild I N4 14! CR&gt; IN 4003

10 Pin Con necto. Bu. 6562 4· 110 Qllo Tra nsinnrs

2Nl906 Q' 2Nl904

Resinor 1/4W 5 ~ 47 K Phi li l'&gt; S C R2S

**270K**

R6 Reaiato r 1/4W l 'lb 14K 3 Philips MR 25F

**R' 3K57**

R' l K58

**ROO 3K.57**

M4U1M4J4 P U Ji PROGRAM METER

PART pESC R I PTlON MEG MfG PARI NJJMBE R

ntt Resistor ! /4 W 1'lb9K 09

**24 K3**

Phfl ipl MR2SF

' lJ ! /4 W 5% 15K

**R&lt;6 82 K**

.n 'OOK

**'20 ' K'**

ea 'OK.n Potentiome ter ' K PT l 0 H 5 K '23 20 K PT 10 H 20K

**20 K**

nz 20 K

' 29 Resistor 1/4 W 5% 15K

**.JO •• 47 K**

.Jl &quot; K

**.J&gt; &quot; K**

nO K.38 lOOK

**82 K**

..e OK'

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2dwNGV6bjktRWM/view?resourcekey=0-XsCaOJv9T140QAJ61ZdZ6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2dwNGV6bjktRWM&resourcekey=0-XsCaOJv9T140QAJ61ZdZ6Q" width="240" alt="1992 - M433 - [DWG 14-060-02-001] - AMPLIFIER ASSEMBLY SCHEMATIC.jpg"></a><br><sub>1992|25 · 14-060-02-001 - AMPLIFIER ASSEMBLY SCHEMATIC · <a href="SCHEMATICS/1992%20-%20M433%20-%20%5BDWG%2014-060-02-001%5D%20-%20AMPLIFIER%20ASSEMBLY%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTFRjTnB6bUlpRWs/view?resourcekey=0-ZOE8ta4wXviPFm6sNN9zXA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTFRjTnB6bUlpRWs&resourcekey=0-ZOE8ta4wXviPFm6sNN9zXA" width="240" alt="1992 - M433 - [DWG 14-060-06-001] - AMPLIFIER ASSEMBLY COMPONENT LAYOUT.jpg"></a><br><sub>1992|25 · 14-060-06-001 - AMPLIFIER ASSEMBLY COMPONENT LAYOUT · <a href="SCHEMATICS/1992%20-%20M433%20-%20%5BDWG%2014-060-06-001%5D%20-%20AMPLIFIER%20ASSEMBLY%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `19xx - [DWG 14-060-02-001].jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M433 - RTO-144 Connections.pdf`

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKandLc0h6d2VYaFU/view?resourcekey=0-wXl6WVktFtYVhKVgqI7HsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKandLc0h6d2VYaFU&resourcekey=0-wXl6WVktFtYVhKVgqI7HsQ" width="240" alt="1992 - M433 - 434 - P001 - Title Page.jpg"></a><br><sub>1992|25 · 434 - P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbTBsbzQta3FtZzA/view?resourcekey=0-Oe0nqega_de9R6e-Dm2KbA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbTBsbzQta3FtZzA&resourcekey=0-Oe0nqega_de9R6e-Dm2KbA" width="240" alt="1992 - M433 - 434 - P002 - 1-1.jpg"></a><br><sub>1992|25 · 434 - P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZjFaR19wWUF2dWs/view?resourcekey=0-cfu9F2OiCTQkvlJr7HgBGQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZjFaR19wWUF2dWs&resourcekey=0-cfu9F2OiCTQkvlJr7HgBGQ" width="240" alt="1992 - M433 - 434 - P003 - 2-1.jpg"></a><br><sub>1992|25 · 434 - P003 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWGhlQk5zbFJWQ0E/view?resourcekey=0-txQShbCfcYsC24rOCMTpXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWGhlQk5zbFJWQ0E&resourcekey=0-txQShbCfcYsC24rOCMTpXg" width="240" alt="1992 - M433 - 434 - P004 - 3-1.jpg"></a><br><sub>1992|25 · 434 - P004 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY3VXeEtWZHRhSWM/view?resourcekey=0-e3i8lVqrlPSiAC1lFd9acQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY3VXeEtWZHRhSWM&resourcekey=0-e3i8lVqrlPSiAC1lFd9acQ" width="240" alt="1992 - M433 - 434 - P005 - 3-2.jpg"></a><br><sub>1992|25 · 434 - P005 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWhldW5waHJvMnc/view?resourcekey=0-0Th7xZyeBMOQjjhbyGVJmA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWhldW5waHJvMnc&resourcekey=0-0Th7xZyeBMOQjjhbyGVJmA" width="240" alt="1992 - M433 - 434 - P006 - 3-3.jpg"></a><br><sub>1992|25 · 434 - P006 - 3-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjV5b2ZDMlByaG8/view?resourcekey=0-hr786v1bRkRlTmc59ZjVWw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjV5b2ZDMlByaG8&resourcekey=0-hr786v1bRkRlTmc59ZjVWw" width="240" alt="1992 - M433 - 434 - P007 - 4-1.jpg"></a><br><sub>1992|25 · 434 - P007 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkRJcUxGSHJ0WW8/view?resourcekey=0-Y1JS_ADEv0m8XDk_kzMTjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkRJcUxGSHJ0WW8&resourcekey=0-Y1JS_ADEv0m8XDk_kzMTjA" width="240" alt="1992 - M433 - 434 - P008 - 4-2.jpg"></a><br><sub>1992|25 · 434 - P008 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWN4R0g0NV84ek0/view?resourcekey=0-h4Di5WLse99L0QNAvlHG4A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWN4R0g0NV84ek0&resourcekey=0-h4Di5WLse99L0QNAvlHG4A" width="240" alt="1992 - M433 - 434 - P009 - 4-3.jpg"></a><br><sub>1992|25 · 434 - P009 - 4-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWhaQWRvTmVYTFE/view?resourcekey=0-8pdvpEFUPEkqz8erKOqudg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWhaQWRvTmVYTFE&resourcekey=0-8pdvpEFUPEkqz8erKOqudg" width="240" alt="1992 - M433 - 434 - P010 - 5-1.jpg"></a><br><sub>1992|25 · 434 - P010 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekdxMXozd3Eycms/view?resourcekey=0-Z6EHKsUdvaM6OrsoFKVLig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekdxMXozd3Eycms&resourcekey=0-Z6EHKsUdvaM6OrsoFKVLig" width="240" alt="1992 - M433 - 434 - P011 - 5-2.jpg"></a><br><sub>1992|25 · 434 - P011 - 5-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbDBrSHZnRWtOQU0/view?resourcekey=0-6qA2hWSrtmphN6ZigFcpww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbDBrSHZnRWtOQU0&resourcekey=0-6qA2hWSrtmphN6ZigFcpww" width="240" alt="1992 - M433 - 434 - P012 - 6-1.jpg"></a><br><sub>1992|25 · 434 - P012 - 6-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlRUNHRhZVhDYTg/view?resourcekey=0-H8rv5HK3vJmtwjSvbQJnxw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlRUNHRhZVhDYTg&resourcekey=0-H8rv5HK3vJmtwjSvbQJnxw" width="240" alt="1992 - M433 - 434 - P013 - 6-2.jpg"></a><br><sub>1992|25 · 434 - P013 - 6-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSjVSazdVSzlJZHc/view?resourcekey=0-rc79-gn9DYZFeTUDxseV8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSjVSazdVSzlJZHc&resourcekey=0-rc79-gn9DYZFeTUDxseV8Q" width="240" alt="1992 - M433 - 434 - P014 - 7-1.jpg"></a><br><sub>1992|25 · 434 - P014 - 7-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd3ZvTS0tOXh2X28/view?resourcekey=0-VmtSeoWXZEUgNMfB_4sFIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd3ZvTS0tOXh2X28&resourcekey=0-VmtSeoWXZEUgNMfB_4sFIg" width="240" alt="1992 - M433 - 434 - P015 - 7-2.jpg"></a><br><sub>1992|25 · 434 - P015 - 7-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNzM0VnYyZ2JGQTA/view?resourcekey=0-KCPc5nysBmZDkfJPvUjhdg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNzM0VnYyZ2JGQTA&resourcekey=0-KCPc5nysBmZDkfJPvUjhdg" width="240" alt="1992 - M433 - 434 - P016 - 7-3.jpg"></a><br><sub>1992|25 · 434 - P016 - 7-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcE9RZUIzX0FMRXc/view?resourcekey=0-9Hze0tZkVO_Hmxl_PS-DIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcE9RZUIzX0FMRXc&resourcekey=0-9Hze0tZkVO_Hmxl_PS-DIg" width="240" alt="1992 - M433 - 434 - P017 - 8-1.jpg"></a><br><sub>1992|25 · 434 - P017 - 8-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ1BCRDYyX1B6MFU/view?resourcekey=0-haarzARWx0_lWsQ-4bGl6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ1BCRDYyX1B6MFU&resourcekey=0-haarzARWx0_lWsQ-4bGl6Q" width="240" alt="1992 - M433 - 434 - Peak Program Meter (2).pdf"></a><br><sub>1992|25 · 434 - Peak Program Meter (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLXg4NlJCRk5RZmM/view?resourcekey=0-yWAjy3TUGK82vAj5G-oXsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLXg4NlJCRk5RZmM&resourcekey=0-yWAjy3TUGK82vAj5G-oXsQ" width="240" alt="1992 - M433 - 434 - Peak Program Meter.pdf"></a><br><sub>1992|25 · 434 - Peak Program Meter</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1992 - M433 - [DWG 14-060-02-001] - AMPLIFIER ASSEMBLY SCHEMATIC.kicad_sch](KICAD/1992%20-%20M433%20-%20%5BDWG%2014-060-02-001%5D%20-%20AMPLIFIER%20ASSEMBLY%20SCHEMATIC.kicad_sch)
- [1992 - M433 - 434 - Peak Program Meter (2) p10.kicad_sch](KICAD/1992%20-%20M433%20-%20434%20-%20Peak%20Program%20Meter%20(2)%20p10.kicad_sch)
- [1992 - M433 - [DWG 14-060-02-001] - 434 - Peak Program Meter (2) p18.kicad_sch](KICAD/1992%20-%20M433%20-%20%5BDWG%2014-060-02-001%5D%20-%20434%20-%20Peak%20Program%20Meter%20(2)%20p18.kicad_sch)
- [1992 - M433 - [DWG 14-060-02-001] - 434 - Peak Program Meter p18.kicad_sch](KICAD/1992%20-%20M433%20-%20%5BDWG%2014-060-02-001%5D%20-%20434%20-%20Peak%20Program%20Meter%20p18.kicad_sch)
- [19xx - [DWG 14-060-02-001].kicad_sch](KICAD/19xx%20-%20%5BDWG%2014-060-02-001%5D.kicad_sch)
- [M433.kicad_sym](KICAD/M433.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
