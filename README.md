# CloudFlareResolver
Bypass bot-anti-ddos detection of Cloudflare

Simply give the html of cloudflare anti-ddos and it will give back jschl-answer to make request!

How?

cloudflare have one javascript to check if you are one bot or not, then my code read this javascript understanding some things like:

!+[] == 1
!![] == 1
1+[]+2 == 12

then you can make maths with this....

example cloudflare code:
AFRwsPU.WlNfklkua-=+((!+[]+!![]+!![]+!![]+[])+(+!![]));
AFRwsPU.WlNfklkua+=+((!+[]+!![]+!![]+!![]+[])+(!+[]+!![]+!![]+!![]+!![]));
AFRwsPU.WlNfklkua-=+((!+[]+!![]+!![]+!![]+[])+(!+[]+!![]+!![]+!![]));
AFRwsPU.WlNfklkua+=+((!+[]+!![]+[])+(!+[]+!![]+!![]+!![]+!![]));
AFRwsPU.WlNfklkua+=+((!+[]+!![]+[])+(!+[]+!![]+!![]+!![]+!![]+!![]+!![]+!![]));
AFRwsPU.WlNfklkua+=+((!+[]+!![]+[])+(!+[]+!![]+!![]+!![]+!![]+!![]));

this is same of:
AFRwsPU.WlNfklkua-=+((1+1+1+1+[])+(+1));
AFRwsPU.WlNfklkua+=+((1+1+1+1+[])+(1+1+1+1+1));
AFRwsPU.WlNfklkua-=+((1+1+1+1+[])+(1+1+1+1));
AFRwsPU.WlNfklkua+=+((1+1+[])+(1+1+1+1+1));
AFRwsPU.WlNfklkua+=+((1+1+[])+(1+1+1+1+1+1+1+1));
AFRwsPU.WlNfklkua+=+((1+1+[])+(1+1+1+1+1+1));

and this is same of:
AFRwsPU.WlNfklkua-=41;
AFRwsPU.WlNfklkua+=45;
AFRwsPU.WlNfklkua-=44;
AFRwsPU.WlNfklkua+=25;
AFRwsPU.WlNfklkua+=28;
AFRwsPU.WlNfklkua+=26;



Donations:
Bitcoin: 179CTXUVJjirnyYjQazHWb1YvkJN3XE815
Paypal: thecruzwtf@gmail.com

Created by CruZ