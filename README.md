# <p align="center">👑・Impostor・👑</p>

<br>
<p align="center">Impostor is a Python obfuscator, it using crypting and object serialization so its hard to deobfuscating it.</p>
<br>

## <p align="left">📚・Example・📚</p>

<br>

### Normal
```python
input('Hello World!')
```

### Obfuscated
```python
__author__ = 'BlueRed_'
__madeBy__ = 'Impostor'
__git__ = 'https://github.com/CSM-BlueRed/Impostor'

# Obfuscated with Impostor

class Gateway():
  def __init__(self, way: bytes, key: int, **ext) -> None: self.way = way;self.key = key; self.module__ = ext.get('__module', None);self.__globals = ext.get('__globals', None);self.__module = ext.get('__module', None); self.__interpreter = ext.get('interpreter', None)
  def Pass(self): exec(eval(eval('chr(95)+chr(95)+chr(105)+chr(109)+chr(112)+chr(111)+chr(114)+chr(116)+chr(95)+chr(95)+chr(40)+chr(34)+chr(109)+chr(97)+chr(114)+chr(115)+chr(104)+chr(97)+chr(108)+chr(34)+chr(41)')).loads(self.module__.b16decode(self.way)), {'__selfObject__': self, '__key__': self.key, '__module': self.module__, '__globals': self.__globals, '__InterpreterObject__': self.__interpreter}); return self
class Interpreter():
  def __init__(self, code: str, layersFunction: bytes, module, globals_, backend: bytes = b'') -> None: self.__module = module;self.layersFunction = layersFunction;self.__globals = globals_;self.code = {'bytes': code, 'str': str(code)}; self.__backend = backend
  def __tunnel(self) -> Gateway: return Gateway(self.__backend, 5524, __module = self.__module, __globals = self.__globals, interpreter = self)
  def Run(self) -> None: decoder = self.__getobject__(); gate = self.__tunnel().Pass();exec(eval(eval(eval('chr(95)+chr(95)+chr(105)+chr(109)+chr(112)+chr(111)+chr(114)+chr(116)+chr(95)+chr(95)+chr(40)+chr(34)+chr(109)+chr(97)+chr(114)+chr(115)+chr(104)+chr(97)+chr(108)+chr(34)+chr(41)')).loads(decoder), {'__selfObject__': self, '__module': self.__module, '__sr_m': eval(eval('chr(95)+chr(95)+chr(105)+chr(109)+chr(112)+chr(111)+chr(114)+chr(116)+chr(95)+chr(95)+chr(40)+chr(34)+chr(109)+chr(97)+chr(114)+chr(115)+chr(104)+chr(97)+chr(108)+chr(34)+chr(41)')), '__globals': self.__globals, 'gate': gate}))
  def __getobject__(self) -> object: func = self.layersFunction; return self.__module.b64decode(func)

Interpreter(b'QZZ~{Rz*fmQEWy?QC4h4QB^TRRaIm{S5;C%R8>k+QZPnZQbk5iQEWy?QC4h4QB^TRRaIm{S5;C%R8>k+QZPnZQbk5iQEWy?S5|CAQB^TRRaIm{S5;C<R8>k+QZPnZQbk5iQEWy?PDXH5QZO}BRaIn0S5;C%R8>k+QZZ|JRz*fmQEY5TR90+7QC3DvRaIm{S5{I^RBK97QZPzFRz*%uQEW;`S5!(xQB^TZRxoTzS5;C*R4{N-QZPnZRz*2ZRcuO1QdCYwQ!p_@RaIz0S8P&3R8>wxQZPnZQbkTrRcuyBQC4t9Q7|z}RaIn0O)yeQR8>k<QZaBtQbk5iRcvrbQC4h4Q7|=ORWM{nQC3n;RBLcjQZPj@QblA=QEWy^QdVq5QB^TZRxo5zS5;C<RaJ0PQZPnZRz)#SQEWy?R#Z+#QdKcSRWN8qS5;C%R8??UQZQ^<R#i?<RcuyBQB+PvR8~q<QZQ&jO)yeSR8>k;QZZ|JQbk5jS8QxZR90+7Q7|=AR%>KJS8GyERBK97Q$<BEQblA=QEW;`QdCY=QB^TRRxo5%S5;C*RBTFCQZPj@Rz^lnS8PT|QdVqLR4_3^RaInKO>9y^R8~q@QZYtaQdLe+QEXC3QC4hKQ7|=ORaIm{O)yeSR8>k;QZZ|JQbk5mRcvfXR90+7Q7|z}S4Ct(S5;C@RBLcjQZQ?JQblY|Q7}?TQC4tOQB^TZRcm7~S5;C%RBTFDQZPngQbjROQEWy^Ra8<%QZO+?RcmBMO)*kJR8>k?QZZIqQbkrzRcuyBQEN_BRaG%zRaIn0S5{I`R8>k+QZZ|JRz*fmRcvHPRaR_9R8=`cRz+k&S5{I)RBUikQZPk&Qblx5QEW~~S5!(xQ7|z>S5;(AS5;C(R8??UQZPnZQbjROQ*1^^Q&dhxQ&llbRcmNMS8P&3R8??OQhHKaQbk5jRcu;FQC4t8R8=)YRcmBQPDN5kR8>k-QZQ9|Rz*fmQEX&LR#t39QdKomR#jw1S8P&JR90|OQZQCpRz*2ZQEWy?S5!(>QB^ThRxo5zS5;O_R4__aQZPnZRz*%vS8PT|QB+PvQ!p_@RWM{)O>0s_RBK9FQZO-EQbkTqQ*3BRQC4h4R8=)gRaIn4O)yeQR8??OQ$<E$Rz*fmQ*25|PDX4+QB^flR%>KJS8GyERBK98QZZF9QblA=QEW;`QdCY=QB^TRRxo5%S5;C*RBTFCQZQ9|QbtBjS8PT|QdVqLR4_3^RaInKO>9y^R8~q@QZYtaRz*2bQEXC3QC4hKQ7|=ORaIm{O)yeSR8>k;QZZ|JQbkTsQEY5TR90+7Q7|z}S4Ct(S5;C@RBLcjQZQ?JQblY|Q7}$PQC4tOQB^TZRcm7~S5;C%RBTFDQZPngQbjROQEWy^R#Z|&QZO+?RcmBMO)*kJR8>k?QZZIqQbkrzRcuyBQdCk!RaG%zRaIn0S5{I`R8>k+QZZ|JRz*fmRcvHPRaR_ORWLb2Rz+k&S5{I)RBUikQZPk&Qblx5QEXC3S5!(>QB^fVRxo5zS5{U;R4__aQZPnZRz)#VQ*1^^R%=F8QB^TRRxo5*O>9y^RBB2?QZQCpQbkTrRcuyBQfo>@R8=)YRcmZcO)yeQR8@3FQ$<QdQbk5iO>0U>QC4h4RaQnzRcmBIS5;C_RBTF8QZPj@Rz*fmQEW;`PDXH5QdUMwRxo5%S5;C}RBTFCQZQOXRz^lnS8PT|QdVq5Q7|z>RaInKO>9y^RaJ0UQZYtaR#h=jQEXC3QC4hKQB^TZRaIm{O)yeSR8>l0QZZ|JQbkryQEY5TR90+7Q7|z>RcmBIS5;C@RBK99QZQ9{Rz+k^QEWy?Q&dt_QdKcjQdMk5S5;O-RBLodQZZUZQbjRNQ*3BRR#Z+^Q&lxnS5;(TQbkfwR8~q?Q&wwvR#h=mQ7}qKQB+bzQ&lljRxoT%O)*kTRBTFDQZZIxQbjROQ*2~NRa8n=R8~qvQEOyFQC3n+RcuOEQ&wwwQdMkERcuN~S5!(xR8=)gR#jw5O)*kbRBLodQZZUZQdMkHQ*1^_QB+DrRWLPFQdMIxS5;C@RcuOGQZO)jRz+-2RWM{oPDXG>Q&vVxRaIj!O>9<9RBLodQZZ|KRz)#TQ*3BRRa8n=R8=)hQZQpNQC3n$RBUiqQ$<C3Rz+-2S8P^DPDX4+R4_4NRz++^S8G;IR8~$%QZZ|KRz)#TQ*3BRRa8zzRaG@%R%>KhS8Gy6RcmlqQZO)jQdKceRWMdaQ)^O1Q&llxR%>KVO>0(4R8~$#QZYthQbjRRS8QlVR#Z+!Q!q74RWM{)O>9z5RBK99Q&wwvQbtZsRWMdaPDX4+R8~q;S4Ct_O)*kRRBTR2QhHKhQbjpZQ*1^^Q&w<AQZO-7RaI<OPDWBnRcuO9QZPnZQbk5iQEWy^R#Z||R8=ukRaIm{S5;C%R8>k+Q&v?lRz)#SRcuB`QC4h4QB^TRRaI<OPDWBtRBLcjQZPnZQbk5iQEWy^R#Z||R4_4NRaIm{S5;C%R8>k+Q&v?lRz)#RS8PT|QC4h4QB^TRRaI<OPDWBrR8??NQZPnZQbk5iQEWy^R#Z||R4_F|RaIm{S5;C%R8>k+Q&v?lRz)#SQ*1^^QC4h4QB^TRRaI<OPDWBrRBK97QZPnZQbk5iQEWy^R#Z||QdKcSRaIm{S5;C%R8>k+Q&v?lRz*2aS8PT|QC4h4QB^TRRaI<OPDWBrR4{N-QZPnZQbk5iQEWy^R#Z||R8=`cRaIm{S5;C%R8>k+Q&v?lRz+-3Q*1^^QC4h4QB^TRRaI<OPDWBrRclI8QZPnZQbk5iQEWy^R#Z||R4_3^RaIm{S5;C%R8>k+Q&v?lRz)#WRcuB`QC4h4QB^TRRaI<OPDWBtR8~q-QZPnZQbk5iQEWy^Rcl67QB^ThRxoT@O)*kPRclT|QZPnZRz*2ZRcvTVQdVq5Q!q7QR%>H0O>0t4RBTFAQ&vV{Rz^lnRcvrbQC4hLQ&vVxRaIz0O)yeSRBTR1QZZ~{Rz)#WRcvHPRa8zzRWLPFQfp*dO)*kXRaJ0QQ$<C2QblY}RWM{oS8GmHQdKo!S4Ct}S8Gy2RBUioQhHKhQbjpXQ*2I1QB+P<Q&lxoQZQsnS5;C_R90|UQ&nqvQbtZsRcuyBQ&wz6Q&l-jRxoT*O)*kJRBTR2QhHKhRz*2aQEX&NS5!__QdKciRaInRQbkfuR8~q@QZZ|KRz-AAS8P&9S5|OUR8=ucS4Ct}O)yeaRBTR2QZaBuRz+4$QEW~~Qfp3CRWLC_RaIm{S5;C%R8>k+QZPk&R#i?;Q7}?SRa8<%R8=)gRxoT%O)yqSRBTR2QZQ^<Qblx6S8QZTS5!__QdKonQblB1O>0s{R8??RQ&v`CQbtZrQ7}$QRcl67QB^fzRxo2QO)yqSRBTR2QZZ~{QbjRNQ*2~PR8&q?QZY(IQEOyES8P&FRBUiqQZZF}Rz+-6Q7}qKQC4tOR8=uyRxoHnO)*kNRclT|QZPk%QbjRSRcvTTQB+PvQ!q7DQfq8eQC3nyRaJ0TQ&wwvR#h=iRcvrbS8Gm1R4_3^RxoT@O)*kNRBUioQZZUZQblxARWMdcQdVq5Q&lx#RaInKS5{I`RBK9DQ$<QdQdLe)QEX^PS5|CQR8=ukS4Ct_O)*kJRBTF9QhHH&QbjRPQ7~3YQdVq5RaG@iQZQs!QbkfuRBTFEQ$<yJQdMM6Rcu;FR%=p4Q!z?ZQdMk5S5;C<RBUimQZZ|JRz)#RQ*2~NRclU0Q7|z>R%>KhPDWBrRcmlrQZPk&Rz-AAS8P^FRcl67QB^fVRxo5%O)*kZRBTFNQhHH&QdLe+Q*1^^QB+P<QdKciS4Ct(S5;C%R8>k+QZPk&Rz+4$RcvTTQC4h4QB^TRRaIm{O)*kNR8>k<QZPnZQbk5iQEWy?QEN^{Q7|z>S5;(BQEXC9RclIEQ&wwwQblY}S8Q5HS8GaDR8=)gRz+-9S5;C(R8>k+QZPnZQbk5iQEX^PR90+7Q&llTRaIm{S5;C%R8>w$Q&wzRQbk5iRWMFSQC4hHP*gBEP*FWS',
            b'4wAAAAAAAAAAAAAAAAQAAAADAAAAQwAAAHN0AAAAdACDAGQBGQB9AHQAgwCgAWQCoQFzGmQAUwB0AIMAZAMZAH0BdACDAGQEGQB9AnwBagJkBRkAfQN8AqADfAOhAX0DfAKgBHwDoQF9A3wCoAV8A6EBfQN8AqAGfAOhAX0DdACDAGQGGQCgB3wDoQF9A3wDUwApB07aCV9fZ2xvYmFsc9oEZ2F0ZdoOX19zZWxmT2JqZWN0X1/aCF9fbW9kdWxl2gVieXRlc9oGX19zcl9tKQjaB2dsb2JhbHPaA2dldNoEY29kZdoJYjg1ZGVjb2Rl2gliNjRkZWNvZGXaCWIzMmRlY29kZdoJYjE2ZGVjb2Rl2gVsb2FkcykE2ghfZ2xvYmFsc9oDb2Jq2gZtb2R1bGVyCQAAAKkAchIAAAD6K0M6XFVzZXJzXElzYWFjXERlc2t0b3BcSW1wb3N0b3JcaW1wb3N0b3IucHnaDFJlbW92ZUxheWVyczkAAABzFgAAAAABCgEQAQoBCgEKAQoBCgEKAQoBEAE=',
            eval(eval('chr(95)+chr(95)+chr(105)+chr(109)+chr(112)+chr(111)+chr(114)+chr(116)+chr(95)+chr(95)+chr(40)+chr(34)+chr(98)+chr(97)+chr(115)+chr(101)+chr(54)+chr(52)+chr(34)+chr(41)')), globals(),
            b'E3000000000000000000000000070000000300000043000000736400000074008300640119007D0074008300640219007D0174008300640319007D0274008300640419007D0374008300640519007D047C026A01640619007D056407640884007D0664097C015F027C067403640A83015F047C04640B1400640C1B007C0566025300290D4EDA095F5F676C6F62616C73DA0E5F5F73656C664F626A6563745F5FDA155F5F496E7465727072657465724F626A6563745F5FDA085F5F6D6F64756C65DA075F5F6B65795F5FDA0562797465736300000000000000000000000002000000030000005700000073160000007C0044005D0C7D0174007C018301010071046400530029014E2901DA04657865632902DA0461726773DA03617267A900720A000000FA2B433A5C55736572735C49736161635C4465736B746F705C496D706F73746F725C696D706F73746F722E7079DA0573656E645F22000000730200000000017A1F496D706F73746F722E476174657761792E3C6C6F63616C733E2E73656E645F54DA086275696C74696E73E908000000E7000000000000F83F2905DA07676C6F62616C73DA04636F6465DA086578656375746564DA0A5F5F696D706F72745F5FDA0473656E642907DA085F676C6F62616C73DA036F626ADA0E696E7465727072657465724F626ADA066D6F64756C65DA036B65797211000000720C000000720A000000720A000000720B000000DA07476174657761791B000000731400000000010A010A010A010A010A010A01080206010A01'
).Run()
```

<br>

## <p align="left">📢・Informations・📢</p>
- `✅` The code can be compiled with PyInstaller and Nuitka.
- `✅` The code can't be brutforced
- `⏹` The code require a good recursion limit (1.000.000)

<br>

## <p align="left">⭐・Repository・⭐</p>
If you like this repository, **star it** ! And if you want to share your opinion, please go to the **repository discussion**. 

<br>

-----

<p align="center"><strong>By BlueRed : <a href="https://github.com/CSM-BlueRed/">github.com/CSM-BlueRed</a></strong></p>
