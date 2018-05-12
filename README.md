# DL2
This is the second version of DL. Lots of bugs fixed.

## Release Note

SERVER
./server/tcpserver.py
./server/data.mp3


CLIENT
./client/tcpclienctmp3.c
./client/a.out
./client/datalinkPC2.c
./client/datalinkPC20212.out


BB1
./tx_little_BB1/datalink_beagle_0.c(backup)
./tx_little_BB1/d_b.out(backup)
./tx_little_BB1/datalink_beagle.c
./tx_little_BB1/d_bbb.out
gcc -o d_bbb.out datalink_beagle.c -lm -lprussdrv


BB2
./tx_little_BB2/recv_bbb/Receiver_beagle.c
./tx_little_BB2/recv_bbb/recv_beagle.out
gcc -o d_bbb.out datalink_beagle.c -lm -lprussdrv


ISSUE
*observed packet lost on client
*observed extra 4 CRC bytes added by router