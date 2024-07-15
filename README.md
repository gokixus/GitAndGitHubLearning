Git, bir versiyon kontrolü sistemidir. Aynı zamanda endüstri standardıdır. Kariyer-geliştirme için çok önemli.

Linus Torvalds, Linux ve Git'i tasarlamıştır.

------------------------------------------

git --> yardım dökümantasyonu

git config --global user.name

git config --global user.email

ls --> Klasör-dökümman açar

pwd --> Hangi konumda olduğunu bilmek için

cd Documents -> Documents klasörünün içine girer

cd .. -> Açtığın konumdan bir konum geriye getirir.

mkdir Documents --> Documents adlı klasörü oluşturur.

touch not.txt --> not.txt dosyasını oluşturur.

rm -> Dosyayı geçici siler.

rm -rf -> Dosyayı kalıcı olarak siliyor.

------------------------------------------

Arayüz tasarlandı -> Giriş ekranı yapıldı -> Veritabanı bağlantısı yapıldı -> Çıkış fonksiyonu yazıldı (bunlar commit)(buradan itibaren ikiye ayrılıyor) -> Resim yazma fonk. (Branch)
																			 -> Mesajlaşma fonk. yazıldı (Branch)

------------------------------------------

git status --> güncel durumu gösterir

git init --> Bağlamak için, herhangi bir çizilip belgeyi takip etmek için.

ls .la --> gizli klasörleri gösterir

git commit -m "-----" --> Commit oluşturup mesaj yazdırır.

git log -> yazdığımız tüm commitleri gösterir.

git commit -a  VEYA git add . --> herşeyi direkt ekleyip içerisine alabilir, direkt commit yapabilir.

git ignore --> görmezden geleceği dosyaları oluşturup bunun içerisinde en baştan hangi dosyaları göremeyeceğimizi belirtmek.

------------------------------------------

en son commiti HEAD-> master yazısını gösterir.

------------------------------------------

git branch feat --> feat adında yeni bir branch eklenir.

git switch feat --> feat'a döner

git merge feat --> master'dayken yazılırsa feat branch'ıyla birleştirir.

git branch -> kaç tane master, branch olduğunu gösterir. Hangi commit'te olduğumuzu gösterir. Yeşil renkte gözükürse oradayızdır.

------------------------------------------

git stash pop --> dışarı atmak, sakladıklarımızı geri yazdırır.

git stash list --> güncel zulaladıklarımızı verir, stashları gösterir.

git stash apply stash@{0}

git restore ----.txt --> en son commit ne durumdaysa ona geri döndürür, yazdıklarını geri alır?

------------------------------------------


git chechokut commit_id

git reset commit_id --> commit id'den sonraki commitleri siler ama içerikleri silmez.

git reset --hard commit_id --> herşeyi siler. Commitleri ve içeriklerini bile.

git revert commit_id --> sırasıyla yapmak gerekir sonra komplike olur.(Commiti silmeden geri commite gider. Bir nevit commit yedekleme gibi)

------------------------------------------


git diff --> Commit arasında içeriklerini neleri değiştirdiğimizi gösterir.

git diff HEAD --> Bir önceki committe içerikleri neleri değiştirdğimizi gösterir.

git diff commmit_id --> O committe yapılan değişiklikleri gösterir.



git merge master

git rebase master -> yeni branş yapılıyor o branştayken master yeni bir güncelleme yapılıyor. Bu komutu yazdığımızda branchı masterdaki bilgileri alıp kendine eklenerek günceller.



------------------------------------------



star -> ödüllendirmek, takdir etmek

forklamak -> bir projesini başkasından alıp kendi hesabına eklemek ?

------------------------------------------

git remote add origin origin https://github.com/gokixus/repoAdi.git  --> repo oluşturur github'da

git push -u origin master -> master'dakileri repo'ya atar.

git push -> herşeyi repo'ya atar.

git pull -> hem fetch hem merge yapar

git fetch origin master --> github'taki yapılan değişiklikleri alacak ve locale getirecek.





git clone https://github.com/gokixus/repoAdi.git --> repoyu kendi bilgisayarımıza yükler.



