# CBT454
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 454 IS FROM PAUL A MOINIL FORMERLY AT J.R.C. COMPUTING    *   FILE 454
//*           CENTRE IN ISPRA, ITALY.  THIS FILE IS THE             *   FILE 454
//*           BASIC MATERIAL TO HIS LARGE COLLECTION                *   FILE 454
//*           OF SOFTWARE WHICH IS ON FILES 454 THRU 459.           *   FILE 454
//*                                                                 *   FILE 454
//*             THERE IS ANOTHER CONTACT PERSON REGARDING THE       *   FILE 454
//*             MATERIALS IN THIS PACKAGE.  HE IS:                  *   FILE 454
//*                                                                 *   FILE 454
//*                             ANTONIO COLOMBO                     *   FILE 454
//*                             F.T.S.I. ITALIA S.p.A.              *   FILE 454
//*                             VIA NAZARIO SAURO, 38               *   FILE 454
//*                             I-20099 SESTO SAN GIOVANNI          *   FILE 454
//*                             ITALY                               *   FILE 454
//*                             +39(0332)786032                     *   FILE 454
//*                       EMAIL ANTONIO.COLOMBO@JRC.IT              *   FILE 454
//*                       EMAIL AZC10@IT.FTSI.FUJITSU.COM           *   FILE 454
//*                                                                 *   FILE 454
//* FILE NAME : ->.SOURCE.FILE0 (BASIC MATERIAL).                   *   FILE 454
//* FOLLOWS A SUMMARY OF CONTENTS :                                 *   FILE 454
//*    $$$DOC     PRELIMINARY NOTES.                                *   FILE 454
//*    $AIRD      ACCOUNTING INFORMATION RECORD DESCRIPTION (MACRO).*   FILE 454
//*    $CEPA      SMF - COMMON EXIT PARAMETER AREA (MACRO).         *   FILE 454
//*    $DEFREG    REGISTERS EQUATES ASSEMBLER MACRO.                *   FILE 454
//*    $FS        GENERATE FULL SCREEN ORDERS AND FIELDS            *   FILE 454
//*               (IBM 3270 DISPLAY) ASSEMBLER MACROS.              *   FILE 454
//*    $HEDIT     HEADER EDIT (BLOCKS LETTERS IN ASSEMBLY LISTINGS) *   FILE 454
//*               ASSEMBLER MACRO.                                  *   FILE 454
//*    $IDENT     MODULE IDENTIFICATION (MACRO).                    *   FILE 454
//*    $SIDTB     SMF - SYSTEM ID'S FACTOR TABLE (MACRO).           *   FILE 454
//*    $SORT      GENERATE IN-LINE SORT ASSEMBLER MACRO.            *   FILE 454
//*    $TEW$..    TSO EASY-WAY OF CODING (MACROS FACILITY).         *   FILE 454
//*    $TSWXA     TEST AND SWITCH ADDRESSING MODE MACRO.            *   FILE 454
//*    $UJVT      SMF - IEFUJV TABLES VECTOR (MACRO).               *   FILE 454
//*    $XENT      ENTER PROGRAM CONTROL ASSEMBLER MACRO.            *   FILE 454
//*    $XRET      RETURN PROGRAM CONTROL ASSEMBLER MACRO.           *   FILE 454
//*    ALLOCGDG   GDG DATA-SET DYNAMIC ALLOCATION TSO COMMAND.      *   FILE 454
//*    AUTHC      COMMAND AUTHORIZATION INTERFACE (TSO).            *   FILE 454
//*    AUTHCTL    EURATOM AUTHORITY CONTROL MODULE.                 *   FILE 454
//*    AUTHSVC    AUTHORIZATION SVC FOR MVS (IGC00###).             *   FILE 454
//*    BIG        CREATE BLOCK CHARACTERS ISPF/PDF EDIT COMMAND.    *   FILE 454
//*    BIGS       CREATE SLANTED BLOCK CHAR. ISPF/PDF EDIT COMMAND. *   FILE 454
//*    BLOCK      CREATE MULTI BLOCK CHAR. ISPF/PDF EDIT COMMAND.   *   FILE 454
//*    CATS       READ SEQUENTIALLY AN O.S. CATALOG ROUTINE.        *   FILE 454
//*    CENTER     CENTER ISPF/PDF EDIT COMMAND.                     *   FILE 454
//*    CNVCLIST   CONVERT CLISTS VB-255 / FB-80.                    *   FILE 454
//*    COMPRESS   COMPRESS ISPF/PDF EDIT COMMAND.                   *   FILE 454
//*    CONCAT     CONCAT TSO COMMAND.                               *   FILE 454
//*    CONT       SET CONTINUATION ISPF/PDF EDIT COMMAND.           *   FILE 454
//*    CONTROL    CONTROL ISPF/PDF EDIT COMMAND.                    *   FILE 454
//*    CP         TSO : CP COMMANDS (VM).                           *   FILE 454
//*    CRY        ENCRYPT/DECRYPT ISPF/PDF EDIT COMMAND.            *   FILE 454
//*    CUT        CUT DATA LINES ISPF/PDF EDIT COMMAND.             *   FILE 454
//*    DASCAN     DIRECT-ACCESS UCB'S LOOKUP ROUTINE.               *   FILE 454
//*    DAUNTY     DIRECT-ACCESS UNIT TYPE ROUTINE.                  *   FILE 454
//*    DAVALL     DIRECT-ACCESS VOLUME ALLOCATION ROUTINE.          *   FILE 454
//*    DECONCAT   DECONCAT TSO COMMAND.                             *   FILE 454
//*    DECRYPT    DECRYPT ISPF/PDF EDIT COMMAND.                    *   FILE 454
//*    DTSO       DISPLAY SOME CONTROL BLOCKS TSO COMMAND.          *   FILE 454
//*    DTUR       DSECT'S TABLES USE ROUTINE (DTUSE).               *   FILE 454
//*    DVTYUN     DEVICE TYPE TO UNIT NAME ROUTINE.                 *   FILE 454
//*    DYNALL     DYNAMIC DATA-SET ALLOCATION ROUTINE.              *   FILE 454
//*    DYNCC      DYNAMIC CONCATENATION-DECONCATENATION ROUTINE.    *   FILE 454
//*    EDITH      EDIT HEADER ROUTINE.                              *   FILE 454
//*    EDITMACS   LIST OF ADDITIONAL LOCAL ISPF EDIT MACROS.        *   FILE 454
//*    EDMODE     EDMODE ISPF/PDF EDIT COMMAND.                     *   FILE 454
//*    EDVIO      ISPF EDIT IN A VIO DATA-SET.                      *   FILE 454
//*    ENCRYPT    ENCRYPT ISPF/PDF EDIT COMMAND.                    *   FILE 454
//*    EOL        SET CURSOR AT END LINE ISPF/PDF EDIT COMMAND.     *   FILE 454
//*    ERASE      TERMINAL ERASE SCREEN ROUTINE (TSO COMMAND).      *   FILE 454
//*    EURACFT    RACF DATA-SET ACCESS TEST TSO COMMAND.            *   FILE 454
//*    EUSID      SYSTEM VARIABLES CLIST TSO COMMAND.               *   FILE 454
//*    EUSMF      SMF VARIABLES CLIST TSO COMMAND.                  *   FILE 454
//*    EUSUB      EURATOM SUBMIT PROGRAM.                           *   FILE 454
//*    FC         FC ISPF/PDF EDIT COMMAND.                         *   FILE 454
//*    FILEINFO   FILEINFO TSO COMMAND.                             *   FILE 454
//*    FILSPACE   FILSPACE ROUTINE.                                 *   FILE 454
//*    FINDMEM    FINDMEM ROUTINE.                                  *   FILE 454
//*    FIXJCL     FIXJCL ISPF/PDF EDIT COMMAND.                     *   FILE 454
//*    FLOWJCL    FLOWJCL ISPF/PDF EDIT COMMAND.                    *   FILE 454
//*    FSPACE     DISPLAY FREE EXTENTS ON VOLUME(S).                *   FILE 454
//*    FSRTN      FULL-SCREEN SERVICE ROUTINES.                     *   FILE 454
//*    GACTN      OBTAIN ACCOUNT NUMBER / PROGRAMMER'S NUMBER RTN.  *   FILE 454
//*    GDGALLR    GDGALLR ROUTINE.                                  *   FILE 454
//*    GDGRESET   GDG UTILITY PROGRAM.                              *   FILE 454
//*    GETPAN     GETPAN ISPF/PDF EDIT COMMAND.                     *   FILE 454
//*    GFDATE     GENERATE DATES ROUTINES.                          *   FILE 454
//*    GPARM      OBTAIN PARM. FIELD ROUTINE.                       *   FILE 454
//*    GGUR       GET GROUP'S USERIDS FROM RACF - ROUTINE.          *   FILE 454
//*    GPARM      OBTAIN PARM. FIELD ROUTINE.                       *   FILE 454
//*    GUAR       GET USERID ACCOUNT FROM SYS1.UADS/TSO - ROUTINE.  *   FILE 454
//*    ICFS       READ SEQUENTIALLY AN ICF CATALOG ROUTINE.         *   FILE 454
//*    INSORT     INCORE SORT SUBROUTINE.                           *   FILE 454
//*    INTRDR     ALLOCATE AN INTERNAL READER TSO COMMAND.          *   FILE 454
//*    ISPCDSN    DATA-SET SELECTION BY CURSOR FROM ISPF DISPLAY.   *   FILE 454
//*    IXTOFMT5   INDEXED VTOC FORMAT-5 INTERFACE ROUTINE.          *   FILE 454
//*    JB         DISPLAY CPU - SRB (I/O) TIME.                     *   FILE 454
//*    JOBCARD    JOBCARD ISPF/PDF EDIT COMMAND.                    *   FILE 454
//*    JOBS       DISPLAY JOBS RUNNING IN THE SYSTEM TSO COMMAND.   *   FILE 454
//*    LISTAX     LISTAX TSO COMMAND.                               *   FILE 454
//*    LISTENQ    LIST ENQ'S FOR A JOB OR USERID TSO COMMAND.       *   FILE 454
//*    LISTNO     LIST MANUAL'S MEMBERS PROGRAM.                    *   FILE 454
//*    LJUST      LEFT JUSTIFY ISPF/PDF EDIT COMMAND.               *   FILE 454
//*    LOCK       TSO COMMAND TO LOCK TERMINAL.                     *   FILE 454
//*    LOGALLOC   LOGALLOC TSO COMMAND.                             *   FILE 454
//*    MOVECOLS   MOVE COLUMNS WITHIN DATA LINES ISPF/PDF EDIT CMD. *   FILE 454
//*    MREAD      READ PO-MEMBERS ROUTINE.                          *   FILE 454
//*    OPCOM      OPERATORS COMMUNICATIONS ROUTINE.                 *   FILE 454
//*    PARA       PARA ISPF/PDF EDIT COMMAND.                       *   FILE 454
//*    PDREAD     READ PARTITIONED DIRECTORY ROUTINE.               *   FILE 454
//*    PDSW       PARTITIONED DATA-SET WHERE FUNCTION TSO COMMAND.  *   FILE 454
//*    PEDIT      PEDIT ISPF/PDF EDIT COMMAND.                      *   FILE 454
//*    PLREAD     READ PARTITIONED LOAD MODULE ROUTINE.             *   FILE 454
//*    PLUG       PLUG DATA INTO LINES ISPF/PDF EDIT COMMAND.       *   FILE 454
//*    PSWR       OBTAIN RACF PASSWORD TSO COMMAND.                 *   FILE 454
//*    RDCHK      READ TAPE DATA-CHECK ROUTINE.                     *   FILE 454
//*    RESUME     RESTORE ISPF/PDF EDIT COMMAND.                    *   FILE 454
//*    RGROUP     CHANGE CURRENT RACF CONNECT GROUP.                *   FILE 454
//*    RJUST      RIGHT JUSTIFY ISPF/PDF EDIT COMMAND.              *   FILE 454
//*    RPROT      RACF PROTECTION TSO COMMAND.                      *   FILE 454
//*    RSVENQ     DISPLAY RESOURCES ENQ'S RESERVE TSO COMMAND.      *   FILE 454
//*    RTIME      GET REMAINING CPU-SRB TIME ROUTINE.               *   FILE 454
//*    R050A90    ENCIPHER-DECIPHER ROUTINE.                        *   FILE 454
//*    SCRSZ      GET CURRENT SCREEN SIZE TSO COMMAND.              *   FILE 454
//*    SKEL       SKEL ISPF/PDF EDIT COMMAND.                       *   FILE 454
//*    SKELCHK    CHECK ")SEL-)ENDSEL" ISPF/PDF EDIT COMMAND.       *   FILE 454
//*    SLINE      SET SEPARATION LINE ISPF/PDF EDIT COMMAND.        *   FILE 454
//*    SRCHRPI    SEARCH A REPLY PENDING IDENTIFICATION ROUTINE.    *   FILE 454
//*    SSCMD      SEND A SYSTEM COMMAND SUBROUTINE.                 *   FILE 454
//*    STCLOK     CLOCK MEASUREMENT ROUTINE.                        *   FILE 454
//*    STRTEST    STCLOK, TIME AND RTIME TEST PROGRAM.              *   FILE 454
//*    SUJVTA     SEARCH IEFUJV - UJVTABLE SUBROUTINE.              *   FILE 454
//*    SUM        SUM A COLUMN OF NUMBERS ISPF/PDF EDIT COMMAND.    *   FILE 454
//*    TRAP       TRAP ISPF/PDF EDIT COMMAND.                       *   FILE 454
//*    TSODSN     DISPLAY DATA-SET ENQ'S TSO COMMAND.               *   FILE 454
//*    TSOENQ     DISPLAY DATA-SET ENQ'S CONFLICTS TSO COMMAND.     *   FILE 454
//*    TXPRINT    PRINT ROUTINE.                                    *   FILE 454
//*    TXPUNCH    PUNCH ROUTINE.                                    *   FILE 454
//*    TXREAD     READ ROUTINE.                                     *   FILE 454
//*    TXSNAP     SNAP DUMP ROUTINE.                                *   FILE 454
//*    UADS       LIST SYS1.UADS TSO COMMAND.                       *   FILE 454
//*    UNIT       DISPLAY INFORMATION ABOUT PHYSICAL DEVICES.       *   FILE 454
//*    UNITS      DISPLAY UNIT NAMES OF SYSTEM DEVICE NAME TABLE.   *   FILE 454
//*    UPDTMACS   UPDATE LIST OF ADDITIONAL LOCAL ISPF EDIT MACROS. *   FILE 454
//*    USERS      DISPLAY USERS TSO COMMAND.                        *   FILE 454
//*    VGPSUB     ISPF VGET-VPUT SUBROUTINE.                        *   FILE 454
//*    VREAD      VARIABLE READ ROUTINE.                            *   FILE 454
//*    VTOCD      VTOC DIRECT READ-WRITE ROUTINE.                   *   FILE 454
//*    VTOCQ      VTOC QUICK SEQUENTIAL READ ROUTINE.               *   FILE 454
//*    VTOCS      VTOC SEQUENTIAL READ ROUTINE.                     *   FILE 454
//*    VTTCAM     TEST TCAM OR VTAM RUNNING ROUTINE.                *   FILE 454
//*    WAITR      DISPLAY ENQ'S CONFLICTS FOR A JOB OR USERID.      *   FILE 454
//*    WPC        WPC TSO COMMAND.                                  *   FILE 454
//*    XTC        EXECUTE TSO COMMANDS AND/OR CLISTS.               *   FILE 454
//*    ZOOM       BROWSE JCL PROCEDURE ISPF/PDF EDIT COMMAND.       *   FILE 454
//*    ----------------                                             *   FILE 454
//*    I S P F  WORLD :                                             *   FILE 454
//*    ----------------                                             *   FILE 454
//*    ALL MEMBERS NAMES STARTING BY PAJ... ARE ISPF MEMBERS WHICH  *   FILE 454
//*    ALLOW YOU AN EASY WAY TO EXECUTE MANY OF THE DISTRIBUTED     *   FILE 454
//*    COMMANDS, AS I.E. :                                          *   FILE 454
//*    PAJPALL    ISPF - DISPLAY DATA-SETS ALLOCATED TO TSO USER.   *   FILE 454
//*    PAJPBLK    ISPF - DISK BLOCK SIZES COMPUTATIONS.             *   FILE 454
//*    PAJPBUMU   ISPF - BROADCAST USER MESSAGES UNLOAD.            *   FILE 454
//*    PAJPPOF    ISPF - VTAM SECONDARY PROGRAM OPERATOR FACILITY.  *   FILE 454
//*    PAJPVQ     ISPF - GRS/ENQ DISPLAY.                           *   FILE 454
//*    THE MEMBERS NAMED CBOOK000, MBKS00, SBOOK0 AND ALL PBOOK...  *   FILE 454
//*    ARE PART OF AN ISPF APPLICATION EXAMPLE GIVING YOU A         *   FILE 454
//*    FACILITY TO MAINTAIN A SET OF IBM MANUALS LISTS.             *   FILE 454
//*                                                                 *   FILE 454
```
