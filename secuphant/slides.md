% (IT) Security Know Lunch

https://pixabay.com/en/safe-vault-steel-door-banking-913452/

---

How to structure it?

What insights should people take home?
- What are really important points
- Different strategies to cope with a pile of stuff that doesn't actually interest them but is important (e.g. how to come up with and manage unique secure passwords)

---

> "If privacy is outlawed, only outlaws will have privacy." -- Phil Zimmermann, creator of PGP

> "Arguing that you don't care about privacy because you have nothing to hide
> is no different than saying you don't care about free speech because you have
> nothing to say." -- Edward Snowden

---

Kein Computer besitzen!
eigenes Verhalten und Crypto! (crypto schützt nicht gegen alles)
die einzelnen Maßnamen schützen gegen konkrete Sachen
(e.g. Festplattenverschlüsselung: HDD kann nicht gelesen werden, wenn der Rechner aus ist)


---

* regelmäßige Updates

---

# Darüber reden wir heute nicht

---

## Physical Security

* wir müssen doch wann anders davon reden

---

## Und trotzdem..

* Lassen Sie Ihr Gepäck nicht unbeaufsichtigt^^
* Bildschirm sperren, wenn man vom Schreibtisch weggeht

---

# Wovon wir heute reden

---

# Sichere Passwörter

---

* nur du kennst es
* oder nur du hast es

---

<img src="img/password_strength.png" height="400">

<small>Credits: [https://www.xkcd.com/936/](https://www.xkcd.com/936/)</small>

---

Was sagt uns der Comic?

* use as many characters as possible
* kurze Passwörter mit ersetzten Zeichen sind schwierig zu merken und leicht zu knacken

---

## Strategien

1. 4 random common words combined together

2. Regel
* favourite song, etc --> take first letters

3. Password manager
* LastPass
* KeePass
* ..

---

Still

* it's ok to write them down but not on a post-it next to the computer screen
(if you otherwise forget them and lock yourself out of your account)

---

Und so wie so:
* alle 6 Monate Password ändern

---

* 2factor auth

[https://twofactorauth.org](https://twofactorauth.org)

---

<img src="img/encrypt-all-the-things.png" height="400">

<small>Credits: [http://csharpner.com/blog/index.php/encrypt-all-the-things-a-guide/](http://csharpner.com/blog/index.php/encrypt-all-the-things-a-guide/)</small>

---

## website traffic:

* https

---

## mail -- gpg

* wer macht das bereits?
* GPG Keys: nur du hast den privaten Schlüssel! Backup!
* Philips idea: make a key signing party! 🎉
* team key abschaffen??
* betreff/metadaten

---

## Why bother?

---

<img src="img/key_cryptocard.jpg" height="400">

<small>Credits:
[https://github.com/ccchh/Cryptoparty-Slides](https://github.com/ccchh/Cryptoparty-Slides)</small>


---

### Problems with unencrypted email

* not private
* doesn't guarantee the identity of the sender

---

### How does email encryption solve this?

* you can encrypt mail meant for particular recepients so that only they are able to decrypt it and read its contents
* you can digitally sign the mail you send which insures others that the you really were the author of the mail

---

### How does it work?

* mathematical operations with large numbers
* asymmetric encryption: uses a pair of 2 keys
* public key: you distribute it to anyone who will be writing to you
* private key: you use it to decrypt the messages
* keep your private key private
* make a backup

---

### What does email encryption _not_ solve?

* who are you talking to when
* subject line

---

We recommend:

<img src="img/thunderbird_logo.jpg" height="200">
<img src="img/Enigmail_Logo.png" height="200">

---

<img src="img/thunderbird_compose.png">

---

## Festplatten

* wer macht das? wer macht das noch nicht?
* regelmäßige Backups (encrypted!)
  * another location
  * make sure they can actually be restored^^
* sensible Information vernichten

---

# Außerdem

---

## smartphones

* noch unsicherer als Rechner^^
* don't load your gpg key on your smart phone!
* messaging (signal)

---

* on a windows machine:
    * antivirus software: keep up to date, run regularly
    * firewall

---

* on a public machine:
    * use privacy mode
    * always log out from services

---

* browser plugins?
 * adblock
 * umatrix
 * https everywhere

 * start page instead of google

---

# 5 Step Action Plan

---

1. Regelmäßig Updates machen
2. Sich eine Passwort-Strategie überlegen und durchziehen
3. Festplatte verschlüsseln
4. Regelmäßige Backups auf eine externe verschlüsselte Festplatte einrichten
5. Verschlüsselte Kommunikation

---

# Fragen?

---

## Lektüreempfehlungen

* https://xeushack.com/choosing-a-strong-password-in-2017/
* Security in a Box: https://securityinabox.org/en/

---

# Danke!

Dieser Vortrag steht unter der [Creative Commons BY-SA Lizenz](https://creativecommons.org/licenses/by-sa/4.0/deed.de).

![by](img/Cc-by_new_white.svg)
![sa](img/Cc-sa_white.svg)

