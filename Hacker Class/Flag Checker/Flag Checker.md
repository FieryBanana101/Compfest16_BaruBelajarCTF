# [500 pts] Flag Checker
### Category: Reverse Engineering

**Deskripsi**
> I created a flag checker so you can check if your flag is valid or not!
>
> Author: Zanark

**FlagChecker.java:**
```java
import java.util.Scanner;public class FlagChecker{public static void main(String[] args){Scanner in=new Scanner(System.in);System.out.print("Enter the flag: ");String f=in.nextLine();if(f.length()!=40){System.out.println("Invalid Flag!");return;}long[]la=new long[f.length()];for(int i=0;i<f.length();i++){la[i]=f.charAt(i);}if(22200*la[0]+15995*la[1]+3774*la[2]+37591*la[3]+41041*la[4]+14515*la[5]+20272*la[6]+18048*la[7]+3558*la[8]+20153*la[9]+26338*la[10]+17313*la[11]+23534*la[12]+8407*la[13]+13272*la[14]+22544*la[15]+4893*la[16]+14236*la[17]+19413*la[18]+22209*la[19]+46441*la[20]+36201*la[21]+1062*la[22]+29034*la[23]+11325*la[24]+680*la[25]+6859*la[26]+34036*la[27]+9970*la[28]+12183*la[29]+7170*la[30]+36992*la[31]+27965*la[32]+20951*la[33]+35984*la[34]+11912*la[35]+45854*la[36]+2761*la[37]+50078*la[38]+23743*la[39]!=71501491){System.out.println("Invalid Flag!");return;}if(2519*la[1]+40678*la[2]+2634*la[3]+37878*la[4]+37203*la[5]+34032*la[6]+39225*la[7]+22371*la[8]+14110*la[9]+49996*la[10]+16462*la[11]+16453*la[12]+47755*la[13]+7577*la[14]+38065*la[15]+52966*la[16]+47305*la[17]+23732*la[18]+17153*la[19]+52125*la[20]+10727*la[21]+26887*la[22]+44587*la[23]+43220*la[24]+4387*la[25]+34631*la[26]+33183*la[27]+7143*la[28]+8531*la[29]+29898*la[30]+41415*la[31]+35597*la[32]+49557*la[33]+11164*la[34]+42390*la[35]+51196*la[36]+6114*la[37]+12690*la[38]+41976*la[39]!=99309784){System.out.println("Invalid Flag!");return;}if(12504*la[2]+39165*la[3]+17348*la[4]+50022*la[5]+28000*la[6]+27014*la[7]+15639*la[8]+4061*la[9]+27692*la[10]+13193*la[11]+41142*la[12]+41040*la[13]+32084*la[14]+27577*la[15]+4836*la[16]+34993*la[17]+34100*la[18]+52264*la[19]+20109*la[20]+4551*la[21]+19609*la[22]+33556*la[23]+30714*la[24]+28091*la[25]+18216*la[26]+18140*la[27]+280*la[28]+33002*la[29]+18676*la[30]+38193*la[31]+12146*la[32]+8738*la[33]+9442*la[34]+5307*la[35]+16889*la[36]+48342*la[37]+3239*la[38]+45992*la[39]!=80476090){System.out.println("Invalid Flag!");return;}if(11538*la[3]+27038*la[4]+49205*la[5]+2160*la[6]+43484*la[7]+19407*la[8]+32096*la[9]+4349*la[10]+47466*la[11]+10907*la[12]+32139*la[13]+48376*la[14]+7090*la[15]+21751*la[16]+19311*la[17]+35417*la[18]+36879*la[19]+17793*la[20]+11854*la[21]+37774*la[22]+35177*la[23]+20000*la[24]+10968*la[25]+51926*la[26]+11506*la[27]+41582*la[28]+14402*la[29]+24311*la[30]+21983*la[31]+20881*la[32]+42676*la[33]+17872*la[34]+217*la[35]+23378*la[36]+26508*la[37]+15770*la[38]+41835*la[39]!=81242468){System.out.println("Invalid Flag!");return;}if(29579*la[4]+19717*la[5]+2792*la[6]+29131*la[7]+50730*la[8]+49815*la[9]+1332*la[10]+28545*la[11]+756*la[12]+39370*la[13]+28389*la[14]+34081*la[15]+38703*la[16]+3864*la[17]+13196*la[18]+51380*la[19]+13797*la[20]+32777*la[21]+2539*la[22]+28259*la[23]+39596*la[24]+34753*la[25]+52535*la[26]+52094*la[27]+41988*la[28]+51138*la[29]+28009*la[30]+47682*la[31]+1951*la[32]+21811*la[33]+4459*la[34]+50119*la[35]+3899*la[36]+3676*la[37]+29753*la[38]+3923*la[39]!=87762821){System.out.println("Invalid Flag!");return;}if(15412*la[5]+8367*la[6]+2918*la[7]+32638*la[8]+26152*la[9]+15593*la[10]+51986*la[11]+5747*la[12]+52792*la[13]+22915*la[14]+43547*la[15]+49186*la[16]+5913*la[17]+16454*la[18]+49860*la[19]+16026*la[20]+8426*la[21]+2704*la[22]+18528*la[23]+25145*la[24]+30654*la[25]+37918*la[26]+29364*la[27]+24858*la[28]+27513*la[29]+5906*la[30]+27245*la[31]+39458*la[32]+46000*la[33]+12950*la[34]+42502*la[35]+26338*la[36]+50108*la[37]+32681*la[38]+30304*la[39]!=80747503){System.out.println("Invalid Flag!");return;}if(36837*la[6]+21509*la[7]+23029*la[8]+37333*la[9]+29775*la[10]+5231*la[11]+8665*la[12]+12563*la[13]+41268*la[14]+18864*la[15]+28920*la[16]+3282*la[17]+24369*la[18]+47236*la[19]+22547*la[20]+51016*la[21]+769*la[22]+14924*la[23]+23397*la[24]+41179*la[25]+20270*la[26]+52899*la[27]+20120*la[28]+3174*la[29]+35993*la[30]+10843*la[31]+9463*la[32]+1876*la[33]+37370*la[34]+8657*la[35]+37679*la[36]+12023*la[37]+15779*la[38]+15178*la[39]!=69153214){System.out.println("Invalid Flag!");return;}if(26894*la[7]+14466*la[8]+244*la[9]+26686*la[10]+45676*la[11]+52361*la[12]+38323*la[13]+50270*la[14]+4744*la[15]+2874*la[16]+29243*la[17]+7852*la[18]+32894*la[19]+1000*la[20]+1331*la[21]+10345*la[22]+18570*la[23]+30546*la[24]+11734*la[25]+48184*la[26]+12003*la[27]+41338*la[28]+47093*la[29]+38797*la[30]+4591*la[31]+7414*la[32]+23231*la[33]+25174*la[34]+42274*la[35]+8332*la[36]+2663*la[37]+29950*la[38]+25671*la[39]!=65769438){System.out.println("Invalid Flag!");return;}if(30186*la[8]+52574*la[9]+29518*la[10]+8686*la[11]+32176*la[12]+22473*la[13]+8773*la[14]+15074*la[15]+25039*la[16]+5249*la[17]+33082*la[18]+8135*la[19]+47201*la[20]+38326*la[21]+37752*la[22]+29697*la[23]+6120*la[24]+12589*la[25]+43052*la[26]+8563*la[27]+26178*la[28]+2730*la[29]+39108*la[30]+19064*la[31]+46910*la[32]+12849*la[33]+32971*la[34]+52711*la[35]+41968*la[36]+11348*la[37]+27840*la[38]+20482*la[39]!=70208258){System.out.println("Invalid Flag!");return;}if(25446*la[9]+11750*la[10]+25398*la[11]+49512*la[12]+24784*la[13]+29164*la[14]+46384*la[15]+32768*la[16]+12740*la[17]+19128*la[18]+22220*la[19]+42844*la[20]+45822*la[21]+35936*la[22]+31289*la[23]+42777*la[24]+27452*la[25]+30200*la[26]+2224*la[27]+49841*la[28]+10956*la[29]+13199*la[30]+44704*la[31]+10762*la[32]+21657*la[33]+26159*la[34]+28112*la[35]+34037*la[36]+48414*la[37]+49626*la[38]+28599*la[39]!=76907030){System.out.println("Invalid Flag!");return;}if(46957*la[10]+11342*la[11]+8534*la[12]+40936*la[13]+37231*la[14]+29001*la[15]+46284*la[16]+34527*la[17]+10266*la[18]+32500*la[19]+47418*la[20]+29462*la[21]+42406*la[22]+27455*la[23]+10082*la[24]+42567*la[25]+29387*la[26]+4733*la[27]+3632*la[28]+3051*la[29]+36953*la[30]+28323*la[31]+23937*la[32]+49848*la[33]+45333*la[34]+13910*la[35]+33817*la[36]+15706*la[37]+50213*la[38]+8392*la[39]!=69058615){System.out.println("Invalid Flag!");return;}if(7604*la[11]+10110*la[12]+26676*la[13]+25203*la[14]+28499*la[15]+12398*la[16]+42375*la[17]+5462*la[18]+7218*la[19]+45704*la[20]+13161*la[21]+7552*la[22]+18566*la[23]+41968*la[24]+35034*la[25]+12156*la[26]+42540*la[27]+6731*la[28]+35925*la[29]+33629*la[30]+19891*la[31]+45321*la[32]+13234*la[33]+27960*la[34]+51749*la[35]+11402*la[36]+9482*la[37]+33252*la[38]+27310*la[39]!=65059742){System.out.println("Invalid Flag!");return;}if(51862*la[12]+33723*la[13]+6900*la[14]+9128*la[15]+43619*la[16]+31787*la[17]+21265*la[18]+21518*la[19]+45003*la[20]+13643*la[21]+45631*la[22]+6851*la[23]+49662*la[24]+6858*la[25]+34265*la[26]+48224*la[27]+9480*la[28]+51894*la[29]+32094*la[30]+4136*la[31]+10619*la[32]+12268*la[33]+18657*la[34]+15670*la[35]+6415*la[36]+36655*la[37]+4493*la[38]+17293*la[39]!=60198088){System.out.println("Invalid Flag!");return;}if(37851*la[13]+7615*la[14]+29369*la[15]+21593*la[16]+39635*la[17]+26749*la[18]+40257*la[19]+13883*la[20]+4983*la[21]+33163*la[22]+30925*la[23]+17441*la[24]+44461*la[25]+27031*la[26]+49079*la[27]+27243*la[28]+25513*la[29]+42324*la[30]+20632*la[31]+44009*la[32]+1227*la[33]+10822*la[34]+13853*la[35]+41929*la[36]+52365*la[37]+330*la[38]+7217*la[39]!=62109682){System.out.println("Invalid Flag!");return;}if(2145*la[14]+23601*la[15]+51936*la[16]+31450*la[17]+5336*la[18]+19281*la[19]+50486*la[20]+456*la[21]+40822*la[22]+2199*la[23]+17238*la[24]+51411*la[25]+10942*la[26]+19149*la[27]+6162*la[28]+12873*la[29]+7842*la[30]+46757*la[31]+17460*la[32]+25397*la[33]+22880*la[34]+31082*la[35]+37746*la[36]+28036*la[37]+28106*la[38]+20255*la[39]!=49547687){System.out.println("Invalid Flag!");return;}if(10480*la[15]+29038*la[16]+37254*la[17]+45560*la[18]+24296*la[19]+47053*la[20]+945*la[21]+34883*la[22]+27600*la[23]+28287*la[24]+35437*la[25]+33919*la[26]+35859*la[27]+3678*la[28]+7909*la[29]+29530*la[30]+23158*la[31]+24750*la[32]+22846*la[33]+36457*la[34]+13404*la[35]+30987*la[36]+32459*la[37]+14590*la[38]+24941*la[39]!=56653732){System.out.println("Invalid Flag!");return;}if(44448*la[16]+33979*la[17]+15795*la[18]+43751*la[19]+37435*la[20]+47741*la[21]+14520*la[22]+50176*la[23]+47386*la[24]+25930*la[25]+45211*la[26]+10713*la[27]+46621*la[28]+3423*la[29]+38548*la[30]+1269*la[31]+16894*la[32]+15177*la[33]+20447*la[34]+27166*la[35]+32701*la[36]+51021*la[37]+31647*la[38]+13210*la[39]!=61430146){System.out.println("Invalid Flag!");return;}if(10116*la[17]+40944*la[18]+33029*la[19]+2425*la[20]+6305*la[21]+25605*la[22]+29139*la[23]+19590*la[24]+32908*la[25]+23233*la[26]+11041*la[27]+33096*la[28]+36493*la[29]+1392*la[30]+17877*la[31]+44207*la[32]+32185*la[33]+4648*la[34]+6244*la[35]+17973*la[36]+29039*la[37]+24269*la[38]+33882*la[39]!=42365683){System.out.println("Invalid Flag!");return;}if(21408*la[18]+6486*la[19]+42414*la[20]+21070*la[21]+47875*la[22]+6781*la[23]+40950*la[24]+46962*la[25]+28041*la[26]+28967*la[27]+27957*la[28]+24886*la[29]+10276*la[30]+42729*la[31]+36256*la[32]+45304*la[33]+27377*la[34]+4471*la[35]+12941*la[36]+15579*la[37]+38684*la[38]+3285*la[39]!=49341834){System.out.println("Invalid Flag!");return;}if(5513*la[19]+48732*la[20]+21922*la[21]+3320*la[22]+25155*la[23]+7087*la[24]+33480*la[25]+20107*la[26]+12259*la[27]+7578*la[28]+5949*la[29]+2058*la[30]+28568*la[31]+10210*la[32]+46165*la[33]+46124*la[34]+7808*la[35]+52940*la[36]+30736*la[37]+23951*la[38]+52822*la[39]!=38630960){System.out.println("Invalid Flag!");return;}if(50139*la[20]+44864*la[21]+36755*la[22]+37320*la[23]+47121*la[24]+28406*la[25]+47165*la[26]+7321*la[27]+44479*la[28]+41794*la[29]+4461*la[30]+42843*la[31]+8369*la[32]+48339*la[33]+16672*la[34]+21941*la[35]+50048*la[36]+28078*la[37]+15718*la[38]+9247*la[39]!=51853879){System.out.println("Invalid Flag!");return;}if(36920*la[21]+13812*la[22]+43415*la[23]+39970*la[24]+26178*la[25]+47699*la[26]+46061*la[27]+45283*la[28]+9500*la[29]+46576*la[30]+6477*la[31]+49537*la[32]+35528*la[33]+38630*la[34]+49077*la[35]+23294*la[36]+26174*la[37]+27267*la[38]+19812*la[39]!=54588207){System.out.println("Invalid Flag!");return;}if(37832*la[22]+30587*la[23]+43018*la[24]+13421*la[25]+27934*la[26]+12342*la[27]+34132*la[28]+36593*la[29]+12006*la[30]+31156*la[31]+8769*la[32]+43315*la[33]+44102*la[34]+33289*la[35]+32282*la[36]+41188*la[37]+16869*la[38]+46457*la[39]!=41799425){System.out.println("Invalid Flag!");return;}if(1246*la[23]+29718*la[24]+22082*la[25]+27619*la[26]+50996*la[27]+52231*la[28]+19018*la[29]+4559*la[30]+50393*la[31]+26059*la[32]+29400*la[33]+12892*la[34]+20202*la[35]+20702*la[36]+40987*la[37]+40725*la[38]+13872*la[39]!=38582518){System.out.println("Invalid Flag!");return;}if(39144*la[24]+38657*la[25]+7248*la[26]+44227*la[27]+48016*la[28]+37462*la[29]+26098*la[30]+49170*la[31]+45509*la[32]+2131*la[33]+48555*la[34]+10974*la[35]+7955*la[36]+52828*la[37]+17842*la[38]+14507*la[39]!=41695164){System.out.println("Invalid Flag!");return;}if(16937*la[25]+8243*la[26]+20552*la[27]+27956*la[28]+10527*la[29]+37030*la[30]+40832*la[31]+21015*la[32]+42255*la[33]+49759*la[34]+25161*la[35]+12321*la[36]+25322*la[37]+41205*la[38]+51643*la[39]!=32858969){System.out.println("Invalid Flag!");return;}if(6926*la[26]+21720*la[27]+7471*la[28]+29479*la[29]+37838*la[30]+4810*la[31]+29424*la[32]+16171*la[33]+23747*la[34]+31798*la[35]+39664*la[36]+35472*la[37]+35661*la[38]+23861*la[39]!=29241675){System.out.println("Invalid Flag!");return;}if(51140*la[27]+51081*la[28]+528*la[29]+29612*la[30]+45986*la[31]+8406*la[32]+37794*la[33]+3180*la[34]+49127*la[35]+13173*la[36]+12539*la[37]+29794*la[38]+51552*la[39]!=29534126){System.out.println("Invalid Flag!");return;}if(37489*la[28]+40823*la[29]+44116*la[30]+7630*la[31]+50475*la[32]+22196*la[33]+5883*la[34]+44062*la[35]+25458*la[36]+49575*la[37]+24359*la[38]+51939*la[39]!=33092466){System.out.println("Invalid Flag!");return;}if(33836*la[29]+33587*la[30]+50181*la[31]+44661*la[32]+24375*la[33]+395*la[34]+41331*la[35]+38713*la[36]+17849*la[37]+26979*la[38]+20564*la[39]!=26761866){System.out.println("Invalid Flag!");return;}if(7642*la[30]+18577*la[31]+49855*la[32]+13072*la[33]+30513*la[34]+48984*la[35]+48078*la[36]+21001*la[37]+36365*la[38]+29228*la[39]!=23909239){System.out.println("Invalid Flag!");return;}if(4477*la[31]+30226*la[32]+45539*la[33]+29796*la[34]+30968*la[35]+18353*la[36]+23724*la[37]+44759*la[38]+891*la[39]!=18416992){System.out.println("Invalid Flag!");return;}if(38940*la[32]+24058*la[33]+31540*la[34]+1162*la[35]+38964*la[36]+4872*la[37]+15287*la[38]+44126*la[39]!=13607624){System.out.println("Invalid Flag!");return;}if(3764*la[33]+24620*la[34]+20299*la[35]+43589*la[36]+6486*la[37]+52544*la[38]+34013*la[39]!=13793910){System.out.println("Invalid Flag!");return;}if(40887*la[34]+38728*la[35]+12557*la[36]+43355*la[37]+30244*la[38]+25711*la[39]!=15726976){System.out.println("Invalid Flag!");return;}if(49093*la[35]+9334*la[36]+32115*la[37]+14976*la[38]+13541*la[39]!=10944962){System.out.println("Invalid Flag!");return;}if(26165*la[36]+9948*la[37]+13084*la[38]+12357*la[39]!=4427998){System.out.println("Invalid Flag!");return;}if(41991*la[37]+27148*la[38]+28723*la[39]!=8606370){System.out.println("Invalid Flag!");return;}if(49990*la[38]+29254*la[39]!=6637224){System.out.println("Invalid Flag!");return;}if(40495*la[39]!=2267720){System.out.println("Invalid Flag!");return;}System.out.println("Correct! Flag: COMPFEST16{"+f+"}");}}
```

### Solusi

Karena source code java tersebut sulit dibaca, source code harus di rapihkan dahulu menggunakan online tools berikut: https://codebeautify.org/javaviewer

**FlagChecker_clean.java:**
```java
import java.util.Scanner;
public class FlagChecker {
  public static void main(String[] args) {
    Scanner in = new Scanner(System.in);
    System.out.print("Enter the flag: ");
    String f = in.nextLine();
    if (f.length() != 40) {
      System.out.println("Invalid Flag!");
      return;
    }
    long[] la = new long[f.length()];
    for (int i = 0; i < f.length(); i++) {
      la[i] = f.charAt(i);
    }
    if (22200 * la[0] + 15995 * la[1] + 3774 * la[2] + 37591 * la[3] + 41041 * la[4] + 14515 * la[5] + 20272 * la[6] + 18048 * la[7] + 3558 * la[8] + 20153 * la[9] + 26338 * la[10] + 17313 * la[11] + 23534 * la[12] + 8407 * la[13] + 13272 * la[14] + 22544 * la[15] + 4893 * la[16] + 14236 * la[17] + 19413 * la[18] + 22209 * la[19] + 46441 * la[20] + 36201 * la[21] + 1062 * la[22] + 29034 * la[23] + 11325 * la[24] + 680 * la[25] + 6859 * la[26] + 34036 * la[27] + 9970 * la[28] + 12183 * la[29] + 7170 * la[30] + 36992 * la[31] + 27965 * la[32] + 20951 * la[33] + 35984 * la[34] + 11912 * la[35] + 45854 * la[36] + 2761 * la[37] + 50078 * la[38] + 23743 * la[39] != 71501491) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (2519 * la[1] + 40678 * la[2] + 2634 * la[3] + 37878 * la[4] + 37203 * la[5] + 34032 * la[6] + 39225 * la[7] + 22371 * la[8] + 14110 * la[9] + 49996 * la[10] + 16462 * la[11] + 16453 * la[12] + 47755 * la[13] + 7577 * la[14] + 38065 * la[15] + 52966 * la[16] + 47305 * la[17] + 23732 * la[18] + 17153 * la[19] + 52125 * la[20] + 10727 * la[21] + 26887 * la[22] + 44587 * la[23] + 43220 * la[24] + 4387 * la[25] + 34631 * la[26] + 33183 * la[27] + 7143 * la[28] + 8531 * la[29] + 29898 * la[30] + 41415 * la[31] + 35597 * la[32] + 49557 * la[33] + 11164 * la[34] + 42390 * la[35] + 51196 * la[36] + 6114 * la[37] + 12690 * la[38] + 41976 * la[39] != 99309784) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (12504 * la[2] + 39165 * la[3] + 17348 * la[4] + 50022 * la[5] + 28000 * la[6] + 27014 * la[7] + 15639 * la[8] + 4061 * la[9] + 27692 * la[10] + 13193 * la[11] + 41142 * la[12] + 41040 * la[13] + 32084 * la[14] + 27577 * la[15] + 4836 * la[16] + 34993 * la[17] + 34100 * la[18] + 52264 * la[19] + 20109 * la[20] + 4551 * la[21] + 19609 * la[22] + 33556 * la[23] + 30714 * la[24] + 28091 * la[25] + 18216 * la[26] + 18140 * la[27] + 280 * la[28] + 33002 * la[29] + 18676 * la[30] + 38193 * la[31] + 12146 * la[32] + 8738 * la[33] + 9442 * la[34] + 5307 * la[35] + 16889 * la[36] + 48342 * la[37] + 3239 * la[38] + 45992 * la[39] != 80476090) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (11538 * la[3] + 27038 * la[4] + 49205 * la[5] + 2160 * la[6] + 43484 * la[7] + 19407 * la[8] + 32096 * la[9] + 4349 * la[10] + 47466 * la[11] + 10907 * la[12] + 32139 * la[13] + 48376 * la[14] + 7090 * la[15] + 21751 * la[16] + 19311 * la[17] + 35417 * la[18] + 36879 * la[19] + 17793 * la[20] + 11854 * la[21] + 37774 * la[22] + 35177 * la[23] + 20000 * la[24] + 10968 * la[25] + 51926 * la[26] + 11506 * la[27] + 41582 * la[28] + 14402 * la[29] + 24311 * la[30] + 21983 * la[31] + 20881 * la[32] + 42676 * la[33] + 17872 * la[34] + 217 * la[35] + 23378 * la[36] + 26508 * la[37] + 15770 * la[38] + 41835 * la[39] != 81242468) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (29579 * la[4] + 19717 * la[5] + 2792 * la[6] + 29131 * la[7] + 50730 * la[8] + 49815 * la[9] + 1332 * la[10] + 28545 * la[11] + 756 * la[12] + 39370 * la[13] + 28389 * la[14] + 34081 * la[15] + 38703 * la[16] + 3864 * la[17] + 13196 * la[18] + 51380 * la[19] + 13797 * la[20] + 32777 * la[21] + 2539 * la[22] + 28259 * la[23] + 39596 * la[24] + 34753 * la[25] + 52535 * la[26] + 52094 * la[27] + 41988 * la[28] + 51138 * la[29] + 28009 * la[30] + 47682 * la[31] + 1951 * la[32] + 21811 * la[33] + 4459 * la[34] + 50119 * la[35] + 3899 * la[36] + 3676 * la[37] + 29753 * la[38] + 3923 * la[39] != 87762821) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (15412 * la[5] + 8367 * la[6] + 2918 * la[7] + 32638 * la[8] + 26152 * la[9] + 15593 * la[10] + 51986 * la[11] + 5747 * la[12] + 52792 * la[13] + 22915 * la[14] + 43547 * la[15] + 49186 * la[16] + 5913 * la[17] + 16454 * la[18] + 49860 * la[19] + 16026 * la[20] + 8426 * la[21] + 2704 * la[22] + 18528 * la[23] + 25145 * la[24] + 30654 * la[25] + 37918 * la[26] + 29364 * la[27] + 24858 * la[28] + 27513 * la[29] + 5906 * la[30] + 27245 * la[31] + 39458 * la[32] + 46000 * la[33] + 12950 * la[34] + 42502 * la[35] + 26338 * la[36] + 50108 * la[37] + 32681 * la[38] + 30304 * la[39] != 80747503) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (36837 * la[6] + 21509 * la[7] + 23029 * la[8] + 37333 * la[9] + 29775 * la[10] + 5231 * la[11] + 8665 * la[12] + 12563 * la[13] + 41268 * la[14] + 18864 * la[15] + 28920 * la[16] + 3282 * la[17] + 24369 * la[18] + 47236 * la[19] + 22547 * la[20] + 51016 * la[21] + 769 * la[22] + 14924 * la[23] + 23397 * la[24] + 41179 * la[25] + 20270 * la[26] + 52899 * la[27] + 20120 * la[28] + 3174 * la[29] + 35993 * la[30] + 10843 * la[31] + 9463 * la[32] + 1876 * la[33] + 37370 * la[34] + 8657 * la[35] + 37679 * la[36] + 12023 * la[37] + 15779 * la[38] + 15178 * la[39] != 69153214) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (26894 * la[7] + 14466 * la[8] + 244 * la[9] + 26686 * la[10] + 45676 * la[11] + 52361 * la[12] + 38323 * la[13] + 50270 * la[14] + 4744 * la[15] + 2874 * la[16] + 29243 * la[17] + 7852 * la[18] + 32894 * la[19] + 1000 * la[20] + 1331 * la[21] + 10345 * la[22] + 18570 * la[23] + 30546 * la[24] + 11734 * la[25] + 48184 * la[26] + 12003 * la[27] + 41338 * la[28] + 47093 * la[29] + 38797 * la[30] + 4591 * la[31] + 7414 * la[32] + 23231 * la[33] + 25174 * la[34] + 42274 * la[35] + 8332 * la[36] + 2663 * la[37] + 29950 * la[38] + 25671 * la[39] != 65769438) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (30186 * la[8] + 52574 * la[9] + 29518 * la[10] + 8686 * la[11] + 32176 * la[12] + 22473 * la[13] + 8773 * la[14] + 15074 * la[15] + 25039 * la[16] + 5249 * la[17] + 33082 * la[18] + 8135 * la[19] + 47201 * la[20] + 38326 * la[21] + 37752 * la[22] + 29697 * la[23] + 6120 * la[24] + 12589 * la[25] + 43052 * la[26] + 8563 * la[27] + 26178 * la[28] + 2730 * la[29] + 39108 * la[30] + 19064 * la[31] + 46910 * la[32] + 12849 * la[33] + 32971 * la[34] + 52711 * la[35] + 41968 * la[36] + 11348 * la[37] + 27840 * la[38] + 20482 * la[39] != 70208258) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (25446 * la[9] + 11750 * la[10] + 25398 * la[11] + 49512 * la[12] + 24784 * la[13] + 29164 * la[14] + 46384 * la[15] + 32768 * la[16] + 12740 * la[17] + 19128 * la[18] + 22220 * la[19] + 42844 * la[20] + 45822 * la[21] + 35936 * la[22] + 31289 * la[23] + 42777 * la[24] + 27452 * la[25] + 30200 * la[26] + 2224 * la[27] + 49841 * la[28] + 10956 * la[29] + 13199 * la[30] + 44704 * la[31] + 10762 * la[32] + 21657 * la[33] + 26159 * la[34] + 28112 * la[35] + 34037 * la[36] + 48414 * la[37] + 49626 * la[38] + 28599 * la[39] != 76907030) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (46957 * la[10] + 11342 * la[11] + 8534 * la[12] + 40936 * la[13] + 37231 * la[14] + 29001 * la[15] + 46284 * la[16] + 34527 * la[17] + 10266 * la[18] + 32500 * la[19] + 47418 * la[20] + 29462 * la[21] + 42406 * la[22] + 27455 * la[23] + 10082 * la[24] + 42567 * la[25] + 29387 * la[26] + 4733 * la[27] + 3632 * la[28] + 3051 * la[29] + 36953 * la[30] + 28323 * la[31] + 23937 * la[32] + 49848 * la[33] + 45333 * la[34] + 13910 * la[35] + 33817 * la[36] + 15706 * la[37] + 50213 * la[38] + 8392 * la[39] != 69058615) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (7604 * la[11] + 10110 * la[12] + 26676 * la[13] + 25203 * la[14] + 28499 * la[15] + 12398 * la[16] + 42375 * la[17] + 5462 * la[18] + 7218 * la[19] + 45704 * la[20] + 13161 * la[21] + 7552 * la[22] + 18566 * la[23] + 41968 * la[24] + 35034 * la[25] + 12156 * la[26] + 42540 * la[27] + 6731 * la[28] + 35925 * la[29] + 33629 * la[30] + 19891 * la[31] + 45321 * la[32] + 13234 * la[33] + 27960 * la[34] + 51749 * la[35] + 11402 * la[36] + 9482 * la[37] + 33252 * la[38] + 27310 * la[39] != 65059742) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (51862 * la[12] + 33723 * la[13] + 6900 * la[14] + 9128 * la[15] + 43619 * la[16] + 31787 * la[17] + 21265 * la[18] + 21518 * la[19] + 45003 * la[20] + 13643 * la[21] + 45631 * la[22] + 6851 * la[23] + 49662 * la[24] + 6858 * la[25] + 34265 * la[26] + 48224 * la[27] + 9480 * la[28] + 51894 * la[29] + 32094 * la[30] + 4136 * la[31] + 10619 * la[32] + 12268 * la[33] + 18657 * la[34] + 15670 * la[35] + 6415 * la[36] + 36655 * la[37] + 4493 * la[38] + 17293 * la[39] != 60198088) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (37851 * la[13] + 7615 * la[14] + 29369 * la[15] + 21593 * la[16] + 39635 * la[17] + 26749 * la[18] + 40257 * la[19] + 13883 * la[20] + 4983 * la[21] + 33163 * la[22] + 30925 * la[23] + 17441 * la[24] + 44461 * la[25] + 27031 * la[26] + 49079 * la[27] + 27243 * la[28] + 25513 * la[29] + 42324 * la[30] + 20632 * la[31] + 44009 * la[32] + 1227 * la[33] + 10822 * la[34] + 13853 * la[35] + 41929 * la[36] + 52365 * la[37] + 330 * la[38] + 7217 * la[39] != 62109682) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (2145 * la[14] + 23601 * la[15] + 51936 * la[16] + 31450 * la[17] + 5336 * la[18] + 19281 * la[19] + 50486 * la[20] + 456 * la[21] + 40822 * la[22] + 2199 * la[23] + 17238 * la[24] + 51411 * la[25] + 10942 * la[26] + 19149 * la[27] + 6162 * la[28] + 12873 * la[29] + 7842 * la[30] + 46757 * la[31] + 17460 * la[32] + 25397 * la[33] + 22880 * la[34] + 31082 * la[35] + 37746 * la[36] + 28036 * la[37] + 28106 * la[38] + 20255 * la[39] != 49547687) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (10480 * la[15] + 29038 * la[16] + 37254 * la[17] + 45560 * la[18] + 24296 * la[19] + 47053 * la[20] + 945 * la[21] + 34883 * la[22] + 27600 * la[23] + 28287 * la[24] + 35437 * la[25] + 33919 * la[26] + 35859 * la[27] + 3678 * la[28] + 7909 * la[29] + 29530 * la[30] + 23158 * la[31] + 24750 * la[32] + 22846 * la[33] + 36457 * la[34] + 13404 * la[35] + 30987 * la[36] + 32459 * la[37] + 14590 * la[38] + 24941 * la[39] != 56653732) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (44448 * la[16] + 33979 * la[17] + 15795 * la[18] + 43751 * la[19] + 37435 * la[20] + 47741 * la[21] + 14520 * la[22] + 50176 * la[23] + 47386 * la[24] + 25930 * la[25] + 45211 * la[26] + 10713 * la[27] + 46621 * la[28] + 3423 * la[29] + 38548 * la[30] + 1269 * la[31] + 16894 * la[32] + 15177 * la[33] + 20447 * la[34] + 27166 * la[35] + 32701 * la[36] + 51021 * la[37] + 31647 * la[38] + 13210 * la[39] != 61430146) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (10116 * la[17] + 40944 * la[18] + 33029 * la[19] + 2425 * la[20] + 6305 * la[21] + 25605 * la[22] + 29139 * la[23] + 19590 * la[24] + 32908 * la[25] + 23233 * la[26] + 11041 * la[27] + 33096 * la[28] + 36493 * la[29] + 1392 * la[30] + 17877 * la[31] + 44207 * la[32] + 32185 * la[33] + 4648 * la[34] + 6244 * la[35] + 17973 * la[36] + 29039 * la[37] + 24269 * la[38] + 33882 * la[39] != 42365683) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (21408 * la[18] + 6486 * la[19] + 42414 * la[20] + 21070 * la[21] + 47875 * la[22] + 6781 * la[23] + 40950 * la[24] + 46962 * la[25] + 28041 * la[26] + 28967 * la[27] + 27957 * la[28] + 24886 * la[29] + 10276 * la[30] + 42729 * la[31] + 36256 * la[32] + 45304 * la[33] + 27377 * la[34] + 4471 * la[35] + 12941 * la[36] + 15579 * la[37] + 38684 * la[38] + 3285 * la[39] != 49341834) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (5513 * la[19] + 48732 * la[20] + 21922 * la[21] + 3320 * la[22] + 25155 * la[23] + 7087 * la[24] + 33480 * la[25] + 20107 * la[26] + 12259 * la[27] + 7578 * la[28] + 5949 * la[29] + 2058 * la[30] + 28568 * la[31] + 10210 * la[32] + 46165 * la[33] + 46124 * la[34] + 7808 * la[35] + 52940 * la[36] + 30736 * la[37] + 23951 * la[38] + 52822 * la[39] != 38630960) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (50139 * la[20] + 44864 * la[21] + 36755 * la[22] + 37320 * la[23] + 47121 * la[24] + 28406 * la[25] + 47165 * la[26] + 7321 * la[27] + 44479 * la[28] + 41794 * la[29] + 4461 * la[30] + 42843 * la[31] + 8369 * la[32] + 48339 * la[33] + 16672 * la[34] + 21941 * la[35] + 50048 * la[36] + 28078 * la[37] + 15718 * la[38] + 9247 * la[39] != 51853879) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (36920 * la[21] + 13812 * la[22] + 43415 * la[23] + 39970 * la[24] + 26178 * la[25] + 47699 * la[26] + 46061 * la[27] + 45283 * la[28] + 9500 * la[29] + 46576 * la[30] + 6477 * la[31] + 49537 * la[32] + 35528 * la[33] + 38630 * la[34] + 49077 * la[35] + 23294 * la[36] + 26174 * la[37] + 27267 * la[38] + 19812 * la[39] != 54588207) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (37832 * la[22] + 30587 * la[23] + 43018 * la[24] + 13421 * la[25] + 27934 * la[26] + 12342 * la[27] + 34132 * la[28] + 36593 * la[29] + 12006 * la[30] + 31156 * la[31] + 8769 * la[32] + 43315 * la[33] + 44102 * la[34] + 33289 * la[35] + 32282 * la[36] + 41188 * la[37] + 16869 * la[38] + 46457 * la[39] != 41799425) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (1246 * la[23] + 29718 * la[24] + 22082 * la[25] + 27619 * la[26] + 50996 * la[27] + 52231 * la[28] + 19018 * la[29] + 4559 * la[30] + 50393 * la[31] + 26059 * la[32] + 29400 * la[33] + 12892 * la[34] + 20202 * la[35] + 20702 * la[36] + 40987 * la[37] + 40725 * la[38] + 13872 * la[39] != 38582518) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (39144 * la[24] + 38657 * la[25] + 7248 * la[26] + 44227 * la[27] + 48016 * la[28] + 37462 * la[29] + 26098 * la[30] + 49170 * la[31] + 45509 * la[32] + 2131 * la[33] + 48555 * la[34] + 10974 * la[35] + 7955 * la[36] + 52828 * la[37] + 17842 * la[38] + 14507 * la[39] != 41695164) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (16937 * la[25] + 8243 * la[26] + 20552 * la[27] + 27956 * la[28] + 10527 * la[29] + 37030 * la[30] + 40832 * la[31] + 21015 * la[32] + 42255 * la[33] + 49759 * la[34] + 25161 * la[35] + 12321 * la[36] + 25322 * la[37] + 41205 * la[38] + 51643 * la[39] != 32858969) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (6926 * la[26] + 21720 * la[27] + 7471 * la[28] + 29479 * la[29] + 37838 * la[30] + 4810 * la[31] + 29424 * la[32] + 16171 * la[33] + 23747 * la[34] + 31798 * la[35] + 39664 * la[36] + 35472 * la[37] + 35661 * la[38] + 23861 * la[39] != 29241675) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (51140 * la[27] + 51081 * la[28] + 528 * la[29] + 29612 * la[30] + 45986 * la[31] + 8406 * la[32] + 37794 * la[33] + 3180 * la[34] + 49127 * la[35] + 13173 * la[36] + 12539 * la[37] + 29794 * la[38] + 51552 * la[39] != 29534126) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (37489 * la[28] + 40823 * la[29] + 44116 * la[30] + 7630 * la[31] + 50475 * la[32] + 22196 * la[33] + 5883 * la[34] + 44062 * la[35] + 25458 * la[36] + 49575 * la[37] + 24359 * la[38] + 51939 * la[39] != 33092466) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (33836 * la[29] + 33587 * la[30] + 50181 * la[31] + 44661 * la[32] + 24375 * la[33] + 395 * la[34] + 41331 * la[35] + 38713 * la[36] + 17849 * la[37] + 26979 * la[38] + 20564 * la[39] != 26761866) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (7642 * la[30] + 18577 * la[31] + 49855 * la[32] + 13072 * la[33] + 30513 * la[34] + 48984 * la[35] + 48078 * la[36] + 21001 * la[37] + 36365 * la[38] + 29228 * la[39] != 23909239) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (4477 * la[31] + 30226 * la[32] + 45539 * la[33] + 29796 * la[34] + 30968 * la[35] + 18353 * la[36] + 23724 * la[37] + 44759 * la[38] + 891 * la[39] != 18416992) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (38940 * la[32] + 24058 * la[33] + 31540 * la[34] + 1162 * la[35] + 38964 * la[36] + 4872 * la[37] + 15287 * la[38] + 44126 * la[39] != 13607624) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (3764 * la[33] + 24620 * la[34] + 20299 * la[35] + 43589 * la[36] + 6486 * la[37] + 52544 * la[38] + 34013 * la[39] != 13793910) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (40887 * la[34] + 38728 * la[35] + 12557 * la[36] + 43355 * la[37] + 30244 * la[38] + 25711 * la[39] != 15726976) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (49093 * la[35] + 9334 * la[36] + 32115 * la[37] + 14976 * la[38] + 13541 * la[39] != 10944962) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (26165 * la[36] + 9948 * la[37] + 13084 * la[38] + 12357 * la[39] != 4427998) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (41991 * la[37] + 27148 * la[38] + 28723 * la[39] != 8606370) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (49990 * la[38] + 29254 * la[39] != 6637224) {
      System.out.println("Invalid Flag!");
      return;
    }
    if (40495 * la[39] != 2267720) {
      System.out.println("Invalid Flag!");
      return;
    }
    System.out.println("Correct! Flag: COMPFEST16{" + f + "}");
  }
}
```
Awalnya dicek bahwa flag tidak valid jika panjang flag bukan 40 karakter.

Kemudian terlihat di dalam source code, program melakukan pengecekan flag dari input sebanyak 40 kali untuk menentukan flag valid atau tidak valid.

Pengecekan dilakukan pada range index elemen flag yang berbeda untuk setiap kondisi,
> Kondisi 1  : flag[0...39]  
> Kondisi 2  : flag[1...39]  
> Kondisi 3  : flag[2...39]  
> .  
> .  
> Kondisi 39  : flag[38...39]  
> Kondisi 40  : flag[39]  

Oleh karena itu, didapat persamaan linear dengan ord(flag[i]) sebagai variabel. Kita bisa mendapat seluruh nilai flag[0...39] dengan menyelesaikan persamaan mulai dari kondisi 40 hingga kondisi 1 secara berurutan. 

Hal ini karena, terlihat bahwa dari kondisi 40 kita langsung mengetahui nilai flag[39]. Kemudian dari kondisi 39 kita bisa mengetahui nilai flag[38] dari nilai flag[39], dan seterusnya.

Untuk implementasi, kita bisa meng-copy paste seluruh if statement dan diubah menjadi string, kemudian kita masukkan seluruh angka pada string tersebut ke dalam array yang akan menampung setiap persamaan linear.

Berikut implementasi solver script menggunakan python: [FlagChecker.py](https://github.com/FieryBanana101/COMPFEST-16_TeamBaruBelajarCTF/blob/main/Hacker%20Class/Flag%20Checker/Flag%20Checker.py)

> Flag: **COMPFEST16{1ts_jUst_l1n3ar_3qu4ti0Ns_br0_c4a88d6fd8}**
