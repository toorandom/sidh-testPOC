# sidh-testPOC
Slow (but fair) implementation of quantum-secure DH key exchange using isogeny crypto

//
// Slow implementation of Supersingular Isogeny Diffie Hellman protocol for
// sharing secret keys over insecure chanels with an attacker with quantum resources.
// Here I have 64-bit of security but you can uncomment eA,eB to get 256 bit (slow).
// 
// This is just for educational purposes, it is vulnerable. Montgomery curves need
// to be used and Montgomery Ladder. More info on this crypto scheme 
// http://b3ck.blogspot.com/2016/08/criptografia-asimetrica-con-curvas.html
//
// Copy and Paste this code in: http://magma.maths.usyd.edu.au/calc/
//
// BUG: If the program fails, re-run. Sometimes the isogeny kernel includes a point
//      at infinity and this needs special treatment but I will fix it soon.
//
//  16-Sep-2018 (Viva Mexico!)
// 
// Eduardo Ruiz Duarte
// rduarte@ciencias.unam.mx
//

