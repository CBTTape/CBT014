# CBT014
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)
This is still a work in progress. GitHub repos will be deleted and created during this period...
~~~~~~~~~~~~~~~~

//***FILE 014 IS FROM SAM GOLOB AND CONTAINS A SERIES OF ARTICLES   *   FILE 014
//*           WRITTEN FOR TECHNICAL SUPPORT MAGAZINE OF NASPA.      *   FILE 014
//*           THIS FILE IS IN IEBUPDTE SYSIN FORMAT.  FOR           *   FILE 014
//*           ADDITIONAL INFORMATION, SEE THE MEMBER CALLED         *   FILE 014
//*           $$$INTRO.  THESE ARE SAM'S OLDER ARTICLES. (SEE       *   FILE 014
//*           FILE 120 FOR THE COLLECTION OF SAM'S "MVS TOOLS AND   *   FILE 014
//*           TRICKS OF THE TRADE" COLUMNS.)                        *   FILE 014
//*                                                                 *   FILE 014
//*           email:  sbgolob@cbttape.org                           *   FILE 014
//*                                                                 *   FILE 014
//*           This file now contains an IEFACTRT exit that (it      *   FILE 014
//*           is believed) can replace the I/O Count system         *   FILE 014
//*           modification, on modern systems.                      *   FILE 014
//*                                                                 *   FILE 014
//*           Even better, Greg Price's IEFU83 exit (included       *   FILE 014
//*           here as member $$IEFU83), will show a lot of          *   FILE 014
//*           information as well.  See member IOCOUN$$ for         *   FILE 014
//*           more detail about this package.                       *   FILE 014
//*                                                                 *   FILE 014
//*           THIS FILE CONSISTS OF ARTICLES SUBMITTED BY SAM       *   FILE 014
//*           GOLOB TO "TECHNICAL SUPPORT" MAGAZINE OF NASPA,       *   FILE 014
//*           THE NATIONAL SYSTEMS PROGRAMMERS ASSOCIATION,         *   FILE 014
//*           HEADQUARTERED IN MILWAUKEE, WISCONSIN.                *   FILE 014
//*                                                                 *   FILE 014
//*           THE MATERIAL PERTAINS LARGELY TO PROGRAMS ON THE CBT  *   FILE 014
//*           TAPE, AND TO TOPICS OF GENERAL SYSTEMS PROGRAMMER     *   FILE 014
//*           INTEREST.  WITH THE KIND PERMISSION OF BOB BECKER,    *   FILE 014
//*           FORMER EDITOR OF "TECHNICAL SUPPORT", THEY ARE BEING  *   FILE 014
//*           DISTRIBUTED WITH THE CBT TAPE TO FURTHER THE          *   FILE 014
//*           USEFULNESS OF OTHER FILES ON THE TAPE, AND THE TAPE   *   FILE 014
//*           IN GENERAL.                                           *   FILE 014
//*                                                                 *   FILE 014
//*           CBTCNR1   -  A COLUMN ON USEFUL PROGRAMS ON THE CBT   *   FILE 014
//*                          TAPE.  INSTALLMENT 1.                  *   FILE 014
//*                                                                 *   FILE 014
//*           CBTCNR2   -  A COLUMN ON USEFUL PROGRAMS ON THE CBT   *   FILE 014
//*                          TAPE.  INSTALLMENT 2.                  *   FILE 014
//*                                                                 *   FILE 014
//*           CBTINTRO  -  AN INTRODUCTION TO THE CBT TAPE IN       *   FILE 014
//*                          GENERAL.  THE ARTICLE SHOWS HOW THE    *   FILE 014
//*                          CBT TAPE CAN IMPROVE YOUR INSTALLATION *   FILE 014
//*                          GREATLY BY PROVIDING POWERFUL TOOLS.   *   FILE 014
//*                          THIS IS MEANT AS AN INTRODUCTION ONLY, *   FILE 014
//*                          AND SUGGESTS A FEW OF THE TOOLS WHICH  *   FILE 014
//*                          THE AUTHOR HAS FOUND USEFUL IN HIS     *   FILE 014
//*                          WORK.                                  *   FILE 014
//*                                                                 *   FILE 014
//*           IOCOUNT   -  DESCRIPTION OF THE AMAZING IO-COUNT ZAP  *   FILE 014
//*                          TO THE OPERATING SYSTEM, WHICH         *   FILE 014
//*                          PROVIDES EXCP-COUNT INFORMATION IN JCL *   FILE 014
//*                          LISTINGS, FOR ALL ALLOCATED DDNAMES.   *   FILE 014
//*                          THE MODIFICATION IS FOUND ON FILE 369  *   FILE 014
//*                          OF THE CBT TAPE.  THIS IS A DETAILED   *   FILE 014
//*                          DESCRIPTION OF HOW TO INSTALL IT.      *   FILE 014
//*                                                                 *   FILE 014
//*           JESART    -  THIS IS A DESCRIPTION OF HOW TO CONVERT  *   FILE 014
//*                          FROM JES2 VERSION 1.3.4 TO THE HIGHER  *   FILE 014
//*                          RELEASES OF JES2.                      *   FILE 014
//*                                                                 *   FILE 014
//*           SMPART    -  I BELIEVE THIS MATERIAL IS FOUND NOWHERE *   FILE 014
//*                          ELSE IN THIS FORM.  THIS ARTICLE IS    *   FILE 014
//*                          MEANT TO INTRODUCE NEW AND OLD SYSTEMS *   FILE 014
//*                          PROGRAMMERS TO THE CONCEPTS OF SMP.    *   FILE 014
//*                          IT CAN BE USED AS A "HOW-TO-DO-IT"     *   FILE 014
//*                          INTRODUCTION TO ANY LEVEL OF SMP.  IT  *   FILE 014
//*                          IS CLEAR, CONCEPTUAL, AND COMPLETELY   *   FILE 014
//*                          STEP-BY-STEP.  IT COVERS CONCEPTS OF   *   FILE 014
//*                          ALL RELEASES OF SMP, BOTH SMP4 AND     *   FILE 014
//*                          SMP/E.  THE ARTICLE WAS TESTED BY      *   FILE 014
//*                          BEING GIVEN TO NON-SYSTEMS-PROGRAMMERS *   FILE 014
//*                          TO READ, AND IS MEANT FOR ANYONE WHO   *   FILE 014
//*                          HAS ANYTHING TO DO WITH MVS SYSTEM     *   FILE 014
//*                          MAINTENANCE.  THIS MEANS NON-TECHNICAL *   FILE 014
//*                          MANAGERS AS WELL AS TECHNICAL PEOPLE.  *   FILE 014
//*                                                                 *   FILE 014
//*           SMPART2   -  COMPLETION OF THE SMPART MATERIAL.       *   FILE 014
//*                          (IT WAS THERE ALL THE TIME, BUT IT     *   FILE 014
//*                          GOT LOST IN THE SHUFFLE.)              *   FILE 014
//*                          THIS IS AN OLD ARTICLE THAT SOMEHOW    *   FILE 014
//*                          WENT MISSING FROM THIS FILE.           *   FILE 014
//*                                                                 *   FILE 014
//*           A SERIES OF THREE ARTICLES HAS BEEN WRITTEN AS        *   FILE 014
//*           A COURSE TO TEACH THE SUBCOMMANDS OF THE FANTASTIC    *   FILE 014
//*           "PDS" PROGRAM THAT CAN BE FOUND ON FILE 182 OF THE    *   FILE 014
//*           CBT TAPE (WITH UTILITIES ON FILE 296).  THESE         *   FILE 014
//*           ARTICLES ARE NOW DISTRIBUTED WITH THE PDS PACKAGE ON  *   FILE 014
//*           FILE 182, AND WILL NOT BE REPEATED HERE.              *   FILE 014
//*                                                                 *   FILE 014
~~~~~~~~~~~~~~~~

