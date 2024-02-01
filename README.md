Bu proje  bir robot süpürge projesinin farklı topolojiler kullanılarak bir motor sürücü kartının tasarımı,üretimi ve gömülü yazılımı oluşturulmuştur.Devrenin şematik tasarımında güç elektroniği bilgilerinden yararlanılmış, LTSpıce programında simülasyonu gerçekleştirilmiş ve breadboard üzerinden devre kurulumu gerçekleştikten sonra pcb çizimi yapılmıştır.Devrenin PCB ve şematik çizimlerinden Altium Desıgner programından yararlanılmıştır.Yazılım kısmında STM32CubeIDE, STMstudıo gibi programlar aracılığıyla HAL kütüphaneleri ile gömülü yazılımı oluşturulmuştur.Devre ile ilgili detaylı bilgiler aşağıda belirtilmiştir.

Devre 6-40v giriş gerilimine sahip olan sağ ve sol olacak şekilde iki motorun kontrolünü sağlayabilecek şekilde tasarımı gerçekleştirilmiştir. Motorlar swıtchler aracılığıyla manuel veya PWM ile motor kontrolü sağlanmaktadır.Sürücü kartında aynı zamanda potansiyometre iki motorun  kontrolü bulunmaktadır. Devre 3 ana bölümden oluşmaktadır.Bunlar sırasıyla Power, Driver ve Lojik devre bölümlerinden oluşmaktadır.Devrenin Power bileşeninde giriş gerilimi değişkenlik gösterebilen bir geriliminin 5 volt sabit çıkış gerilimi oluşturabilen bir voltaj regülatörü kullanılmıştır. Devrenin lojik tasarımında mantık kapılarından faydalanarak karnaugh diyagramları çıkarılmış ve bu diyagramlar ile devreyi en sade haline getirerek and ve nand kapılarıyla lojik devre tasarımı gerçekleştirilmiştir. Devrenin Driver bloğunda Totem-pole gate driver tekniği ile kontrol transistöleri birleştirilerek sürücü bloğu oluşturulmuştur. Devre EMI VE EMC standartlarına uygun bir şekilde tasarlanmıştır.


![MOT_DV (1)](https://github.com/MUHAMMETGULER35/TOTEM_POLE_GATE_WITH_H_BRIDGE_MOTOR_DRIVER_CARD/assets/156583959/09ebc0b8-e7c4-4a16-a1ad-9608f84aeb65)
![MOTOR_DRIVER_TOP_LAYER](https://github.com/MUHAMMETGULER35/TOTEM_POLE_GATE_WITH_H_BRIDGE_MOTOR_DRIVER_CARD/assets/156583959/b7155f55-f104-47d8-860a-bdc2f6d10f95)
![MOTOR_DRIVER_BOTTOM_LAYER](https://github.com/MUHAMMETGULER35/TOTEM_POLE_GATE_WITH_H_BRIDGE_MOTOR_DRIVER_CARD/assets/156583959/2a0e5699-7b4f-477c-bad3-a804dec22233)
![MOTOR_DRIVER_4_LAYER_PCB](https://github.com/MUHAMMETGULER35/TOTEM_POLE_GATE_WITH_H_BRIDGE_MOTOR_DRIVER_CARD/assets/156583959/a9db0a4d-638e-4a88-a11f-3c653b665ebc)



