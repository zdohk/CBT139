~~~~~~~~~~~~~~~~

//***FILE 139 is from Dennis Longnecker from the Administrator      *   FILE 139
//*           of the Court of the State of Washington.  For         *   FILE 139
//*           additional information see the member called $$DOC.   *   FILE 139
//*           This file is in IEBUPDTE SYSIN format and contains    *   FILE 139
//*           the following members:                                *   FILE 139
//*                                                                 *   FILE 139
//*            email:   dennis.longnecker@courts.wa.gov             *   FILE 139
//*                                                                 *   FILE 139
//*           JESEX008  EXIT 8 WHICH WILL SCAN THE JOB'S JCT AND    *   FILE 139
//*                     FIND OUT THE MAX ABEND CODE FOR THE GIVEN   *   FILE 139
//*                     JOB.  THIS PROGRAM MUST BE IN COMMON        *   FILE 139
//*                     STORAGE.  I ADD AN ENTRY IN IEALPAXX TO     *   FILE 139
//*                     LOAD MY VERSION FROM A LINKLIST LIBRARY     *   FILE 139
//*                     (SYS2.LINKLIB).                             *   FILE 139
//*                                                                 *   FILE 139
//*           JESEX016  THIS PROGRAM WORKS IN CONJUNCTION WITH EXIT *   FILE 139
//*                     8.  IT TAKES WHATEVER DATA IS IN THE        *   FILE 139
//*                     JCTUSER1 FIELD AND SENDS IT TO THE USER.    *   FILE 139
//*                                                                 *   FILE 139
//*           OACJCT    SINCE THE JES JCT AND THE MVS JCT USE THE   *   FILE 139
//*                     SAME NAME FOR SOME OF THE FIELDS, AND EXIT  *   FILE 139
//*                     8 USES BOTH JCT'S THERE IS A COMPILE ERROR  *   FILE 139
//*                     IF YOU DON'T DO SOMETHING ABOUT IT.         *   FILE 139
//*                                                                 *   FILE 139
//*           SAS#BLOCK THIS IS A LITTLE SAS PROGRAM WHICH USES A   *   FILE 139
//*                     FDR VTOC LIST AND GIVES RECOMMENDED         *   FILE 139
//*                     BLOCKSIZES FOR THE TYPE OF DEVICE THE DATA  *   FILE 139
//*                     SET IS ON.                                  *   FILE 139
//*                                                                 *   FILE 139
//*           TERMPROG  THIS IS A CICS PROGRAM WHICH DISPLAYS ALL   *   FILE 139
//*                     THE TERMINALS SIGNED ON THE SYSTEM.  IF     *   FILE 139
//*                     YOU PUT THE CURSOR NEXT TO A TERMINAL NAME  *   FILE 139
//*                     AND PRESS ENTER, DETAILED INFORMATION       *   FILE 139
//*                     ABOUT THE TERMINAL IS DISPLAYED.            *   FILE 139
//*                                                                 *   FILE 139
//*           TESTPRTR  IS A PROGRAM WHICH TESTS VTAM PRINTERS.  IT *   FILE 139
//*                     ALSO LOOKS AT THE BIND IMAGE SENT AND SENDS *   FILE 139
//*                     A MESSAGE TO THE PRINTER TELLING IT WHAT    *   FILE 139
//*                     TYPE OF PRINTER IT IS.                      *   FILE 139
//*                                                                 *   FILE 139
//*           WHOHAS    TSO command to discover enqueues to a       *   FILE 139
//*                     dataset.  Uses GQSCAN service.  S.Golob     *   FILE 139
//*                     added code to end the program with an =     *   FILE 139
//*                     sign, or BYE, or QUIT.  You can adjust      *   FILE 139
//*                     the code in case any dataset names start    *   FILE 139
//*                     with these letters.  Ending the program     *   FILE 139
//*                     with a null command, can't be done if you   *   FILE 139
//*                     are using TSO Session Manager--at least     *   FILE 139
//*                     not easily.                                 *   FILE 139
//*                                                                 *   FILE 139
~~~~~~~~~~~~~~~~

