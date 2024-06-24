# Nubit
Düğümün kurulması :

Düğümünüze Putty veya terminal aracılığıyla bağlanın ve aşağıdaki komutları çalıştırın :
```
sudo apt-get update && sudo apt-get upgrade -y 
```
Install the Dependecies :

Bağımlılıkların yüklenmesi 5 dakika kadar sürebilir
```
sudo apt-get install curl screen git-all build-essential glibc-source pkg-config libssl-dev clang git-lfs -y
```
"nubit" adında yeni bir screen oturumu oluşturun :
```
screen -S nubit
```
Işık düğümünüzü başlatmak için aşağıdaki komutu çalıştırmanız yeterlidir :
```
curl -sL1 https://nubit.sh | bash
```
Ctrl + A D tuşlarına basın ve screen'den çıkın.

Cüzdan kelimelerinizi kaydedin (24 Kelime):
```
sudo cat $HOME/nubit-node/mnemonic.txt
```
İsterseniz düğüm günlüklerinizi kontrol edebilirsiniz (İSTEĞE BAĞLI)":
```
screen -r nubit
```
Tebrikler ışık düğümü görevini (Aşama -2) Başarıyla tamamladınız :)

Aşama 1: Topluluk Toplantısı
Anımsatıcı kelimelerinizi kaydettikten sonra Aşama 1 görevlerini tamamlamanıza izin verir:

Düğüm görevinden aldığınız 24 anımsatıcı kelimeyi Keplr Cüzdan'a aktarın

İçe aktardıktan sonra [alpha.nubit.org](https://alpha.nubit.org/) adresine gidin ve keplr cüzdanına bağlanın

Artık ana sayfada nubit adresinizi görebilirsiniz

Bu adresi kopyalayın ve ekranın sağ üst kısmındaki Nubit Faucet'e gidin.

Adresinizi ve talep musluğunuzu yapıştırın (belki ilerideki görevlerde faydalı olabilir)

Şimdi 1. aşamanın puanlarını almak için [Galxe 1](https://app.galxe.com/quest/Nubit/GCMt1tdj4s?referral_code=GRFr2JOjO6m7VSPv5tsGJfGhT7b0vx05YuqnBOD4FFTZbA=) [Galxe 2](https://app.galxe.com/quest/Nubit/GCYMytdMuz) görevini tamamlayın

Galxe görevini tamamladıktan sonra [alpha.nubit.org](https://alpha.nubit.org/) adresine gidin ve galxe hesabınızı bağlayın

Başarıyla bağlandıktan sonra 3000 kazanılan puan gösterilecek ve tüm görevler tamamlandı olarak işaretlenecek

Tebrikler Aşama 1 ve Aşama 2'yi başarıyla tamamladınız.

Aşama 2 için puanı da https://alpha.nubit.org/ sitesine girdikten sonra aşağıdaki kod ile PubKeyinizi öğrenip verify ediyoruz ve 3000 puan daha almış oluyoruz :
```
$HOME/nubit-node/bin/nkey list --p2p.network nubit-alphatestnet-1 --node.type light
```
![Screenshot_77](https://prnt.sc/Pp9aAymcjNqP)

Buraya giriyoruz : 
![Screenshot_77](https://prnt.sc/GRJdtQESPf1a)
