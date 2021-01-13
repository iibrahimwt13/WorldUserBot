
# OLYPUS USERBOT

# Zeus Usta

### Botu Kurmanın Kolay Yolu
APP ID ve API HASH'ı şuradan alın: [HERE](https://telegram.dog/OtoMyTelegramBot) ve BOT TOKEN buradan [Bot Father](https://t.me/botfather) ve Ardından Aşağıdaki Butona  Basarak StringSession Alınız. Stringinizi Aldıktan sonra Aşağıda Pembe Heroku Butonuna Basıp Deploy İşlemini Başlatınız

[![Get string session](https://repl.it/badge/github/brsitolmyers/exelonstringalici)](https://exelonstringalici.bristolmyers.repl.run/)

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
<p align="center">
  <a href="https://github.com/BristolMyers/ExelonUserBot/fork">
    <img src="https://img.shields.io/github/forks/BristolMyers/ExelonUserBot?label=Fork&style=social">

  </a>
  <a href="https://github.com/BristolMyers/ExelonUserBot">
    <img src="https://img.shields.io/github/stars/BristolMyers/ExelonUserBot?style=social">
  </a>
</p>


<a href="https://resimyukle.xyz/i/VR5AKT"><img src="https://i.resimyukle.xyz/VR5AKT.jpg" /></a> Zeus(https://heroku.com/deploy)


### Güncellemeler için [buraya](https://t.me/ExelonUserBot) tartışma ve hatalar için [buraya](https://t.me/ExelonSupport) katılın.

### Normal Yol

Örnek bir `local_config.py` dosyası şöyle olabilir:

**Tüm değişkenler zorunlu değildir**

__Userbot, yalnızca ilk iki değişkeni ayarlayarak çalışmalıdır__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

### UniBorg Yapılandırması



**Heroku Yapılandırması**
Yapılandırmayı olduğu gibi bırakın.

**Local Yapılandırma**

Neyse ki UniBorg Destek Yapılandırması için zorunlu değişkenler yoktur.

## Zorunlu Değişkenler

- Ortam değişkenlerinden yalnızca ikisi zorunludur.
- Bunun nedeni `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`

    - `APP_ID`:   Bu değeri şuradan alabilirsiniz: https://telegram.dog/OtoMyTelegramBot
    - `API_HASH`:   Bu değeri şuradan alabilirsiniz: https://telegram.dog/OtoMyTelegramBot
- Exelon zorunlu değişkenleri ayarlamadan çalışmayacaktır.
