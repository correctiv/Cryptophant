# Checklist for the Setup of Thunderbird + Enigmail

## Set up Thunderbird/Apple Mail with people's email account

* boot Thunderbird/Mail
* select "use existing email account" in the setup dialog
* copy person's email address into the field

### Incoming/Outgoing Options

* for incoming mail select "IMAP" as protocol
* for outgoing mail select "SMTP"
* enter mail server of person's mail provider
* select encryption mechanism (the email provider should have a help page where
  they describe what they use; it's where you can look up the mail server, the
  encryption method, and the authentication method)

## Install gpg (encryption tools)
(people should've actually installed all of these, but just in case)

* on a Linux system you need to make sure the `gpg` package is installed (it
  mostly is, by default)
* on a MAC-OS you need to install gpg tools (https://gpgtools.org/)
  (here's a detailed tutorial for that:
  http://support.gpgtools.org/kb/how-to/erste-schritte-wo-fange-ich-an#setupkey)
* on Windows you need to install gpg4win ((https://gpg4win.org/))

## Set up gpg-tools + Mail on a MAC

### Set up GPG-Keyring

* open "gpg keyring"
* create key
* upload key to a key server: go to "Keys" -> "Upload to key server"
* to search for other people's keys: go to "Keys" -> "Search on key server";
  enter person's name; select person; select "Download key"

### Use Encryption in MAIL

* in a create mail window, you should now see the menu "Open-PGP" which blinks
 in green
* below the subject line, on the right hand side, there is a padlock symbol;
  it's black, if encryption is activated and gray, if not


## Set up Enigmail (Windows/Linux)

* in Thunderbird's menu go to "Add-ons"
* in the "Extensions" tab search for "Enigmail" and follow installation
  instructions; after installation finishes, restart Thunderbird
* if no Enigmail Wizard appears, go to "Enigmail" in Thunderbird's menu
* select "Standard Configuration"
* select the email account you're creating the key for, click "next" --> this
  triggers key-pair creation (this takes a bit)
* create revocation certificate, store this somewhere safe (you back-up hard
 drive..)
* you're done

### Upload key on keyserver

* go to "Enigmail" -> "Key Management" in the Thunderbird menu
* select your key, right click on it, select "upload to key server"

### Test it: send an encrypted mail

* select "Write"
* in the mail creation dialog, activate the padlock (mail is encrypted), the
  pen (mail is signed) and the paper clip with "Attach my public key" (this
  would allow recepients to directly import your key from your message)
* if your system doesn't have a key for the person you are writing to, it will
  prompt you to select one; there you can alternatively click on "Search for
  key on key server"
