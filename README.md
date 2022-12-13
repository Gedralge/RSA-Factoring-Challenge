
From Wikipedia, the free encyclopedia
Jump to navigationJump to search
The RSA Factoring Challenge was a challenge put forward by RSA Laboratories on March 18, 1991[1] to encourage research into computational number theory and the practical difficulty of factoring large integers and cracking RSA keys used in cryptography. They published a list of semiprimes (numbers with exactly two prime factors) known as the RSA numbers, with a cash prize for the successful factorization of some of them. The smallest of them, a 100-decimal digit number called RSA-100 was factored by April 1, 1991. Many of the bigger numbers have still not been factored and are expected to remain unfactored for quite some time, however advances in quantum computers make this prediction uncertain due to Shor's algorithm.

In 2001, RSA Laboratories expanded the factoring challenge and offered prizes ranging from $10,000 to $200,000 for factoring numbers from 576 bits up to 2048 bits.[2][3][4]

The RSA Factoring Challenges ended in 2007.[5] RSA Laboratories stated: "Now that the industry has a considerably more advanced understanding of the cryptanalytic strength of common symmetric-key and public-key algorithms, these challenges are no longer active."[6] When the challenge ended in 2007, only RSA-576 and RSA-640 had been factored from the 2001 challenge numbers.[7]

The factoring challenge was intended to track the cutting edge in integer factorization. A primary application is for choosing the key length of the RSA public-key encryption scheme. Progress in this challenge should give an insight into which key sizes are still safe and for how long. As RSA Laboratories is a provider of RSA-based products, the challenge was used by them as an incentive for the academic community to attack the core of their solutions — in order to prove its strength.

The RSA numbers were generated on a computer with no network connection of any kind. The computer's hard drive was subsequently destroyed so that no record would exist, anywhere, of the solution to the factoring challenge.[6]

The first RSA numbers generated, RSA-100 to RSA-500 and RSA-617, were labeled according to their number of decimal digits; the other RSA numbers (beginning with RSA-576) were generated later and labelled according to their number of binary digits. The numbers in the table below are listed in increasing order despite this shift from decimal to binary.


Contents
1	The mathematics
2	The prizes and records
3	See also
4	Notes
The mathematics
RSA Laboratories states that: for each RSA number n, there exists prime numbers p and q such that

n = p × q.
The problem is to find these two primes, given only n.

The prizes and records
The following table gives an overview over all RSA numbers. Note that the RSA Factoring Challenge ended in 2007[5] and no further prizes will be awarded for factoring the higher numbers.

The challenge numbers in white lines are part of the original challenge and are expressed in base 10, while the challenge numbers in yellow lines are part of the 2001 expansion and are expressed in base 2
RSA number	Decimal digits	Binary digits	Cash prize offered	Factored on	Factored by
RSA100	100	330	US$1,000[8]	April 1, 1991[9]	Arjen K. Lenstra
RSA110	110	364	US$4,429[8]	April 14, 1992[9]	Arjen K. Lenstra and M.S. Manasse
RSA120	120	397	US$5,898[8]	July 9, 1993[10]	T. Denny et al.
RSA129 [a]	129	426	US$100	April 26, 1994[9]	Arjen K. Lenstra et al.
RSA130	130	430	US$14,527[8]	April 10, 1996	Arjen K. Lenstra et al.
RSA140	140	463	US$17,226	February 2, 1999	Herman te Riele et al.
RSA150	150	496	 	April 16, 2004	Kazumaro Aoki et al.
RSA155	155	512	US$9,383[8]	August 22, 1999	Herman te Riele et al.
RSA160	160	530	 	April 1, 2003	Jens Franke et al., University of Bonn
RSA170 [b]	170	563	 	December 29, 2009	D. Bonenberger and M. Krone [c]
RSA576	174	576	US$10,000	December 3, 2003	Jens Franke et al., University of Bonn
RSA180 [b]	180	596	 	May 8, 2010	S. A. Danilov and I. A. Popovyan, Moscow State University[11]
RSA190 [b]	190	629	 	November 8, 2010	A. Timofeev and I. A. Popovyan
RSA640	193	640	US$20,000	November 2, 2005	Jens Franke et al., University of Bonn
RSA200 [b] ?	200	663	 	May 9, 2005	Jens Franke et al., University of Bonn
RSA210 [b]	210	696		September 26, 2013[12]	Ryan Propper
RSA704 [b]	212	704	US$30,000	July 2, 2012	Shi Bai, Emmanuel Thomé and Paul Zimmermann
RSA220 [b]	220	729	 	May 13, 2016	S. Bai, P. Gaudry, A. Kruppa, E. Thomé and P. Zimmermann
RSA230 [b]	230	762	 	August 15, 2018	Samuel S. Gross, Noblis, Inc.
RSA232 [b]	232	768	 	February 17, 2020[13]	N. L. Zamarashkin, D. A. Zheltkov and S. A. Matveev.
RSA768 [b]	232	768	US$50,000	December 12, 2009	Thorsten Kleinjung et al.[14]
RSA240 [b]	240	795	 	Dec 2, 2019[15]	F. Boudot, P. Gaudry, A. Guillevic, N. Heninger, E. Thomé and P. Zimmermann
RSA250 [b]	250	829	 	Feb 28, 2020[16]	F. Boudot, P. Gaudry, A. Guillevic, N. Heninger, E. Thomé and P. Zimmermann
RSA260	260	862	 	
RSA270	270	895	 	
RSA896	270	896	US$75,000[d]	
RSA280	280	928	 	
RSA290	290	962	 	
RSA300	300	995	 	
RSA309	309	1024	 	
RSA1024	309	1024	US$100,000[d]	
RSA310	310	1028	 	
RSA320	320	1061	 	
RSA330	330	1094	 	
RSA340	340	1128	 	
RSA350	350	1161	 	
RSA360	360	1194	 	
RSA370	370	1227	 	
RSA380	380	1261	 	
RSA390	390	1294	 	
RSA400	400	1327	 	
RSA410	410	1360	 	
RSA420	420	1393	 	
RSA430	430	1427	 	
RSA440	440	1460	 	
RSA450	450	1493	 	
RSA460	460	1526	 	
RSA1536	463	1536	US$150,000[d]	
RSA470	470	1559	 	
RSA480	480	1593	 	
RSA490	490	1626	 	
RSA500	500	1659	 	
RSA617	617	2048	 	
RSA2048	617	2048	US$200,000[d]	
 RSA-129 was not part of the RSA Factoring Challenge, but was related to a column by Martin Gardner in Scientific American.
 The number was factored after the challenge ended.
 RSA-170 was also independently factored by S. A. Danilov and I. A. Popovyan two days later.[11]
 The challenge ended before this prize was awarded.
See also
RSA numbers, decimal expansions of the numbers and known factorizations
LCS35
The Magic Words are Squeamish Ossifrage, the solution found in 1993 to another RSA challenge posed in 1977
RSA Secret-Key Challenge
Integer factorization records
Notes
 Kaliski, Burt (18 Mar 1991). "Announcement of "RSA Factoring Challenge"". Retrieved 8 March 2021.[dead link]
 Leyden, John (25 Jul 2001). "RSA poses $200,000 crypto challenge". The Register. Retrieved 8 March 2021.
 RSA Laboratories. "The New RSA Factoring Challenge". Archived from the original on 2001-07-14.
 RSA Laboratories. "The RSA Challenge Numbers". Archived from the original on 2001-08-05.
 RSA Laboratories. "RSA Factoring Challenge". Archived from the original on 2013-09-21. Retrieved 2008-08-05.
 RSA Laboratories. "The RSA Factoring Challenge FAQ". Archived from the original on 2013-09-21. Retrieved 2008-08-05.
 RSA Laboratories. "The RSA Challenge Numbers". Archived from the original on 2013-09-21. Retrieved 2008-08-05.
 "Status/news report on RSA data security factoring challenge (as of 3/30/00)". 30 January 2002.
 RSA Honor Roll
 Denny, T.; Dodson, B.; Lenstra, A. K.; Manasse, M. S. (1994). On the factorization of RSA-120. Advances in Cryptology — CRYPTO' 93. Lecture Notes in Computer Science. Vol. 773. pp. 166–174. doi:10.1007/3-540-48329-2_15. ISBN 978-3-540-57766-9.
 Danilov, S. A.; Popovyan, I. A. (9 May 2010). "Factorization of RSA-180" (PDF). Cryptology ePrint Archive.
 RSA-210 factored, mersenneforum.org
 INM RAS news
 Kleinjung, Thomas (18 Feb 2010). "Factorization of a 768-bit RSA modulus" (PDF).
 Thomé, Emmanuel (December 2, 2019). "795-bit factoring and discrete logarithms". cado-nfs-discuss (Mailing list).
 Zimmermann, Paul (February 28, 2020). "Factorization of RSA-250". cado-nfs-discuss (Mailing list).
