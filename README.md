# Duty-Free-Shop

Duty Free Shop

Description

Pedro travelled to Europe to take part in the International Olympiad in Informatics and is coming back home. Since all his friends asked him to bring them some gift, he bought two big bags of chocolates (one of Mindt and one of Lilka). Each of these two bags contains a certain number of small chocolates. Buying those two bags was much less expensive than buying smaller, individual boxes of chocolates. At home, Pedro has some empty chocolate boxes that he kept from other trips. Pedro intends to distribute the chocolates he just bought into these smaller boxes, to give them to his friends. 

As soon as Pedro begins filling the small boxes, he realizes he has a big problem: since he has two different brands of chocolates, if he mixes chocolates of different brands into one small box, the friend who receives this small box will discover Pedro's trick to save money, and will not be pleased with him. 

You must help poor Pedro distribute the chocolates into the small boxes in such a way that every small box is completely full, and contains only one brand of chocolates. A number of chocolates may however be left unassigned to any box (Pedro will keep these chocolates to himself).

Input

The input contains several instances of the problem. Each instance consists of three lines. The first line contains two integers M and L that indicate respectively the number of chocolates Mindt and Lilka Pedro bought (0 <= M, L <= 1000). The next line contains an integer N representing the number of small boxes Pedro has (N <= M+L). The third line contains N integers indicating the capacity Ci > 0 of box number i (that is, the number of chocolates needed to fill that box). The end of input is indicated by M = L = 0.

Output

For each instance of the input your program must produce one line of output. If it is possible to distribute the chocolates as defined in the problem statement, print the number of boxes to be filled with Mindt chocolate, followed by a space, followed by the list of box numbers, in ascending order. Each box number in the list should be followed by a space. If it is impossible to distribute the chocolates,print "Impossible to distribute". If more than one solution exists, print any one.

Sample Input

12 9
4
5 2 8 5
100 120
5
21 32 110 54 3
0 0

Sample Output

3 1 2 4
Impossible to distribute
