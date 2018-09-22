# sidh-testPOC
<br><br>
Slow proof of concept (POC) implementation of Supersingular Isogeny Diffie Hellman protocol for<br>
sharing secret keys over insecure chanels having an attacker with quantum resources.<br>
Here I have 64-bit of security but you can uncomment eA,eB to get 256 bit (slower but fair).<br><br> This is just for educational purposes, it is vulnerable. Montgomery curves need<br>
to be used and Montgomery Ladder. More info on this crypto scheme <br>
http://b3ck.blogspot.com/2016/08/criptografia-asimetrica-con-curvas.html<br>
<br>
Copy and Paste this code in: http://magma.maths.usyd.edu.au/calc/<br><br>
16-Sep-2018 (Viva Mexico!)<br>
22-Sep-2018 (Fixed bug, now keys always work with probability 1 once generated)<br><br>
Eduardo Ruiz Duarte<br>
rduarte@ciencias.unam.mx<br>

