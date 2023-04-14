# kendimenotlar
node testnetlerinde kullandığım genel komutlar
# pwd hangi dizinde olduğumuzu göstermek için:
bulunduğumuz klasörden geri gitmek için: # cd ..
bir klkasör ya da dizin oluşturmak için: # mkdir
boş bir dizini silmek için: # rmdir
içi dolu bir klasörü silmek için: # rm -rf klasör adı
dosya içeriğini ekrana yazdırmak için: # echo
# cd .. (iki noktayla) bir üst dizine gitmek için
# cd direkt olarak ana klasöre gitmek için
# cd- (tireli) bir önceki dizine gitmek için
# touch  komutu metin belgesi oluşturur
# $ wget ... link  komutu siteden bir dosya çekmek için kullanılır

disk alanını kontrol etme komutu: df- h
winscp gizli dosyaları kontrol etme komutu: ctrl+alt+h
hetznerde raid o yapmak için; önce siteden rescue yap sonra reset exucuvetion kısmından sonra putty gir ve installimage yaz ubuntu 
# sudo apt update && sudo apt upgrade -y
# sudo apt-get install
# sudo apt install screen
tüm kütüphanleri indirmek yüklemek için;
sudo apt install make clang pkg-config libssl-dev build-essential git jq ncdu bsdmainutils htop net-tools lsof --yes
Yeni bir screen açmak için # screen -S anasayfa 
screenden çıkmak için # ctrl +a+d
tüm screenleri görmek için # screen -ls 
screen içine girmek için # screen -r anasayfa
detached yapmak için # screen -d anasayfa
screen silme komutu # screen -X -S anasayfa quit
# ls bir dosyayı veya klasörleri gösterir
# ls -al| more   dizindeki bütün dosyaları gösterir
# ls -a gizli dosyları gösterir
mavi olanlar klasör, yeşil olanlar ise dosya
vps in adını ve özelliklerini görüntülemek için:  # hostnamectl
vps'in adını değiştirmek için; # hostnamectl set-hostname test
Bağlantı noktalarını ve socket kullanan hizmetler de dahil olmak üzere, açık tüm TCP veya UDP portlarını listelemek için: # sudo netstat -tunlp
Sonuçları filtrelemek istiyorsanız grep komutunu kullanın. Örneğin, 8080 numaralı TCP bağlantı noktasında hangi işlemin dinlediğini bulmak için şunu yazmanız gerekir:
sudo netstat -tnlp | grep :8080
