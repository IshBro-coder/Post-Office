# Post-Office
Assignment done in my Honors CS Class


PROBLEM 1: APCS POST OFFICE
The APCS Post Office is going online and needs you to write the algorithm to determine the postage for entered mail. The class and the weight of a piece of mail determines postage. The length of a piece of mail is always the side parallel to the written address. The following mutually exclusive definitions are used to determine a postage class and cost:

REGULAR POSTCARD: The length must be between 3.5 and 4.25 inches, inclusive. The width must be between 3.5 and 6 inches, inclusive. The thickness must be between .007 and .016 inches, inclusive. The cost to mail is $0.20 per .0625 pounds.

LARGE POSTCARD: The length must be between 4.25 and 6 inches. The width must be between 6 and 11.5 inches. The thickness must be between .007 and .016 inches, inclusive. The cost to mail is $0.30 per .0625 pounds.

ENVELOPE: The length must be between 3.5 and 6.125 inches, inclusive. The width must be between 5 and 11.5 inches, inclusive. The thickness must be between .016 and .25 inches.  The cost to mail is $0.47 per .0625 pounds.

LARGE ENVELOPE: The length must be between 6.125 inches and 24 inches. The width must be between 11 and 18 inches, inclusive. The thickness must be between .25 and .5 inches, inclusive. The cost to mail is $0.56 per .0625 pounds.

PACKAGE: Use package class when the item exceeds any of the rules for “large envelope” and when the length plus the distance around the other sides of a package equals 84 inches or less. The cost to mail is $1.50 per .50 pounds
Note: The “length plus the distance around the other sides of a package” is the length plus the perimeter of the width and thickness of the package.
Length + (Width + Width + Thickness + Thickness)

LARGE PACKAGE: Use a large package class when the length plus the distance around the other sides of a package is more than 84 inches but is not more than 130 inches. The cost to mail is $1.75 per .50 pounds.

UNMAILABLE: Any item that does not conform to any of the above requirements.
INPUT: There will be 5 input lines. Each line will contain 4 rational numbers that represent in order the length, width, thickness and weight in pounds of a piece of mail.

OUTPUT: For each input, print the postage cost according to the rules above. All money amounts must be rounded to two decimal places.  Note carefully how the cost is calculated in Sample Output #2.  If the piece is unmailable, then print “UNMAILABLE”. 

SAMPLE INPUT						SAMPLE OUTPUT
1.  	4, 4, .009, .0015						1. 	$.20
2.  	5, 7, .013, .07						2. 	$.60
3. 	5, 7, .2, .20						3. 	$1.88
4. 	10, 12, .4, .3125						4. 	$2.80
5. 	10, 12, 30, 4.75						5. 	$17.50
