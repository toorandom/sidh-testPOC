# sidh-testPOC
Slow (but fair) implementation of quantum-secure DH key exchange using isogeny crypto<br><br><
<br>
 Slow implementation of Supersingular Isogeny Diffie Hellman protocol for<br>
 sharing secret keys over insecure chanels with an attacker with quantum resources.<br>
 Here I have 64-bit of security but you can uncomment eA,eB to get 256 bit (slow).<br><br>
 This is just for educational purposes, it is vulnerable. Montgomery curves need<br>
 to be used and Montgomery Ladder. More info on this crypto scheme <br>
 http://b3ck.blogspot.com/2016/08/criptografia-asimetrica-con-curvas.html<br><br>
 Copy and Paste this code in: http://magma.maths.usyd.edu.au/calc/<br><br>
 BUG: If the program fails, re-run. Sometimes the isogeny kernel includes a point<br>
      at infinity and this needs special treatment but I will fix it soon.<br><br>
  16-Sep-2018 (Viva Mexico!)<br><br>
 Eduardo Ruiz Duarte<br>
 rduarte@ciencias.unam.mx<br>
<br><br>


