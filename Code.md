The multiplicative Cipher can be decoded by using this formula: 

a^(-1) * C mod 26. Since the encoder can only use this function (C=3 * P mod 26), and we are solving for P, we end up with a^(-1) * C mod 26. a can only be odd numbers up to 26, by punching through every combination of a

By knowing all of the inverses of a, this becomes a lot easier.

normal a: 

1	3	5	7	9	11	15	17	19	21	23	25
	 	 	 	 	 	 	 	 	 	 	 
inverse a: 

1	9	21	15	3	19	7	23	11	5	17	25

There is an [Easy Decode](https://www.ti89.com/cryptotut/multi4.htm) in which you can just plug in your coded message and numbers and it will decode for you.
