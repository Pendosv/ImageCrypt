# Crypto image

_Исполнение [проекта](https://github.com/AlexGyver/crypto) [AlexGyver'а](https://github.com/AlexGyver) на Python by [Pend0s](https://github.com/Pendosv)_

---

### Инструкция:
```
mkdir Image_Crypt
cd Image_Crypt
git clone https://github.com/Pendosv/ImageCrypt.git
virtualenv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```
----

### Использование через GUI:
```
python main.py
```
[![Пример](https://i.ibb.co/pvGxP0f/crypto.png)]()

---

### Использование через консоль:

Для **зашифровки**: 
```
python encrypt.py <image_name> <message> <key>
```
**Результат**: Сохраненная картинка _results\result.bmp_

---

Для **расшифровки**: 
```
python decrypt.py <image_name> <key>
```
**Результат**: Расшифрованное сообщение