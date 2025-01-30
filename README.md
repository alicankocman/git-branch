# (Feature Branch Workflow)  EASY TASK   

 
* Adım 1: Projenizi yerel makinenize 'clone' edin.

``` Terminal
“git clone https://github.com/kullanici_adi/python_script.git”

```
* Adım 2: Proje dizinine gidin ve yeni bir dal (branch) oluşturun.

 Bu örnekte, dalın adını 'new-feature' olarak belirleyelim.

 ``` Terminal

 git checkout -b new-feature

```
* Adım 3: new-feature dalında çalışabilirsiniz. Bir Python dosyasını ('example.py') düzenleyin ve 'print' ifadesi ekleyin
``` Terminal
print("Bu yeni bir özellik!")
```
* Adım 4: Şimdi bu değişikliği commit edin.
``` Terminal
git add example.py
git commit -m "Yeni özellik eklendi"

```

* Adım 5: Bu dalı (branch) GitHub'a geri 'push' edin.

``` Terminal

git push origin new-feature

```
* Adım 6: GitHub hesabınıza gidin. 'New pull request' düğmesine tıklayın ve yeni 'new-feature' dalınızı (branch) 'master' dalına (branch) karşı bir 'pull request' oluşturun.

* Adım 7: 'Pull request inceleyin ve  'pull request 'merge' edin.
