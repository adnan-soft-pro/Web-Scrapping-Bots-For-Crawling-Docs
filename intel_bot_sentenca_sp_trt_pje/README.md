# Requirement
Installation Use python2.7 or python3.6

sudo apt-get install wkhtmltopdf

pip2.7 install -r requirements.txt

python2.7 setup.py install

Install Latest Firefox Browser


### IMPORTANTLY Run one time in terminal session
```
sudo su
export DISPLAY=:20
Xvfb :20 -screen 0 1366x768x16 &
```

#### With number
parse() - return pdf text or None
```
>>> from intel_bot_sentenca_sp_trt_pje.trtsp_jus_parser import Bot
>>> b = Bot(headless=True, digital_user='admin', digital_password='123098')
>>> search_words = [u"Sentença"]
>>> b.parse('0001329-25.2012.5.01.0341', search_words)
```