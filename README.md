# Eger-kaggle-de-LightGBM-de-JSON-characters-hatasi

Eger kaggle de LightGBM de JSON characters hatasi aliyorsaniz yapmanz gereken cok basit.
Model kurarken ilk olarak karakter duzeltmesi yapmaniz gerekir.
Model Fonksiyonunun ilk satirina asagidaki kodu yazmaniz yeterli 
Daha sonra test ve train diye bolun. ;-)


all_data.columns = ["".join (c if c.isalnum() else "_" for c in str(x)) for x in all_data.columns]
