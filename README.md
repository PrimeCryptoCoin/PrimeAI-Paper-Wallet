# 🔐 PrimeAI Paper Wallet

A paper wallet is a physical document containing your private and public keys. It is considered one of the most secure ways to hold PrimeAI because it keeps your keys completely offline and safe from online hacking attempts. 

Follow these steps to create your PrimeAI paper wallet:

1. Download the `primeai-paper-wallet.html` file

2. For extra security, ensure you are offline before generating your wallet. Disconnect your computer from the internet to protect against any online threats.

3. Run the `primeai-paper-wallet.html` file locally on your computer.

4. Follow the on-screen instructions and move your cursor randomly or type jibberish into the box to generate your new paper wallet.

5. Once your wallet has been created, print it out immediately.

6. Verify that the printed document contains your public and private keys in raw and QR code format.

7. Store the printed paper wallet in a safe and secure location, like a safe or a safety deposit box. Treat it as you would cash or other valuables.

⚠️ Remember, if you lose your paper wallet or if it gets damaged to the point that the keys are not legible, you will lose access to your PrimeAI. There is no way to recover your funds without your keys, so keep them secure and consider making backups.

For additional security, it is recommended to laminate your paper wallet to protect against physical damage and use a secure container for storage.

Your PrimeAI paper wallet is now ready to receive funds! To send or check your balance, you will use the public key (visible on the paper wallet). Always keep your private key confidential, as anyone with access to it can control your PrimeAI funds.

The "load and verify" wallet address refers to the public address of your PrimeAI wallet. This is the address you share with others to receive PrimeAI coins. It's akin to an email address that you'd give out to receive messages. However, anyone can also use this address to check the balance of the wallet on the blockchain because it's part of the public ledger.

The private key, on the other hand, is like a password. It is a secret key that is used to access and send your coins from the wallet address. Anyone with access to your private key can control the PrimeAI funds associated with your public address. Therefore, it should be kept secure and never shared with anyone.

# Adding your public address as a "Watch Wallet" to primeai-qt:
To add a wallet address as a watch-only wallet in the primeai-qt wallet software, you essentially add it to your wallet interface to keep an eye on its balance and transactions without having the ability to spend any of the coins (since you arent exposing the private key).

1. Open your primeai-qt wallet software.
2. Navigate to the 'File' menu and select 'Open URI' or similar option.
3. Enter the public wallet address that you wish to watch.
4. Confirm the addition, and the software will add the address onto your wallet interface.

Now, the primeai-qt interface will show the balance of the watched wallet, but remember, without the corresponding private key, you cannot send transactions from this wallet.

Always remember that if you are importing the wallet as a watch wallet, you are not "loading" the full wallet, just monitoring it, since the private keys are not inputted into the software.

# Procedure for Importing a Paper Wallet **private key** into the QT Wallet:

1) Perform a clean installation on a system without any previous wallet (ensure the absence of the .primeai directory). Prior to deletion, safeguard your seed words.

2) Run ./primeaid in one terminal window.

3) In another terminal window, execute ./primeai-cli importprivkey "MY-PRIVATE-KEY-GENERATED-ON-PAPER-WALLET".

4) Close the ./primeaid window (CTRL-C).

5) Open the QT wallet, set a passphrase, allow it to synchronize for a few minutes, and start enjoying your wallet.

END USER NOTES:

 1) For Bulk Wallet I recommended using Google Chrome, it's the fastest.

 2) Requires IE9+, Firefox, Chrome or sufficient JavaScript support.

 3) Mobile Safari only works with iPhone4 or newer devices.
    Older devices timeout while executing JavaScript.

 4) DO NOT use Opera Mini it renders JavaScript output server side, therefore
    they might record the private key you generated.

 5) BIP38 most likely will not work on mobile devices due to hardware limitations.

# PrimeAI Paper Wallet Generator
JavaScript Client-Side PrimeAI Wallet Generator

Instructions:

Download and run primeai-paper-wallet.html

Print wallet and keep private key secure!

Now PrimeAI addresses and their corresponding private key can be conveniently 
generated in a web browser.

The PrimeAI - PrimeAI project provides an all-in-one HTML document with embedded
JavaScript/Css/Images. The JavaScript is readable not minified and contains no
XMLHttpRequest's (no AJAX). The benefit of this technique is you can load the 
JavaScript locally and trust that the JavaScript did not change after being 
loaded. 


Please send DONATIONS for this project to Bitcoin Address (original developer): 
1NiNja1bUmhSoTXozBRBEtR8LeF9TGbZBN




Notice of Copyrights and Licenses:
---------------------------------------
The bitaddress.org project, PrimeAI software and embedded resources are
copyright bitaddress.org.

The PrimeAI name and logo are not part of the open source
license.

Portions of the all-in-one HTML document contain JavaScript codes that
are the copyrights of others. The individual copyrights are included
throughout the document along with their licenses. Included JavaScript
libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:

JavaScript function	|	License
-------------------	|	--------------
Array.prototype.map	|	Public Domain
window.Crypto | BSD License
window.SecureRandom	| BSD License
window.EllipticCurve	|	BSD License
window.BigInteger |	BSD License
window.QRCode | MIT License
window.Bitcoin | MIT License

The PrimeAI - Paper Wallet software is available under The MIT License (MIT)
Copyright (c) 2023

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
