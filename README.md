# Xv6_qemu
Adding a date command to Xv6 


# INTRODUCTION

Adding a new system call to xv6 called the date command.The  new system call will get the current time and return it to the user program. We made use of the   helper function, cmostime() (defined in lapic.c), to read the real time clock from the system (ubuntu) and  date.h contains the definition of the struct rtcdate struct, which you will provide as an argument to cmostime() as a pointer.
We  created  a user-level program that calls your new date system call named date.c


(Plz follow intstructions.txt for changes to be made in different files)
