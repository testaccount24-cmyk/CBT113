# CBT113
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 113 IS FROM COMMERCIAL UNION INSURANCE COMPANIES IN       *   FILE 113
//*           BOSTON MASS AND CONTAINS A COPY OF THEIR SMPSCAN      *   FILE 113
//*           SYSTEM. THE SMPSCAN PROGRAM WAS FIRST DEVELOPED AS A  *   FILE 113
//*           GENERAL UTILITY TO REPLACE OUR EARLIER PTSSCAN        *   FILE 113
//*           PROGRAM AND HELP US WITH SPECIAL CIRCUMSTANCES THAT   *   FILE 113
//*           ARE NOT HANDLED WELL BY SMP/E.  SMPSCAN READS SMP/E   *   FILE 113
//*           LIST DATA SETS AS INPUT AND CAN DO ELEMENT SELECTION  *   FILE 113
//*           AND CROSS - ZONE MATCHING FOR UP TO 16 LISTINGS       *   FILE 113
//*           CONCURRENTLY.  THE MAXIMUM NUMBER OF LISTINGS THAT    *   FILE 113
//*           CAN BE CONCURRENTLY PROCESSED IS EASILY CHANGED       *   FILE 113
//*           THROUGH RECOMPILATION.  THE PROGRAM DOES WHAT IT WAS  *   FILE 113
//*           DESIGNED TO DO,  BUT SETUP CAN BE A BIT UNWIELDY.  WE *   FILE 113
//*           HAD TO DECIDE WHETHER TO DEVELOP A BOOLEAN ALGEBRA    *   FILE 113
//*           INPUT AND CODE A SYNTAX CHECKER,  OR USE ARRAYS AND   *   FILE 113
//*           FILL THEM UP USING PL/I GET DATA. WE FOUND THE CHOICE *   FILE 113
//*           FAIRLY EASY TO MAKE.  THE SAMPLE MEMBERS (FILES 113   *   FILE 113
//*           AND 114) SHOULD BE OF HELP TO SOMEONE TRYING TO USE   *   FILE 113
//*           THE PROGRAM.  LAST YEAR WE USED SMPSCAN AS A          *   FILE 113
//*           PERFORMANCE TUNING AID TO HELP RELIEVE VIRTUAL        *   FILE 113
//*           STORAGE CONSTRAINTS IN MVS/XA SO WE COULD INCREASE    *   FILE 113
//*           THE PRIVATE AREA SIZE BELOW 16M FOR CICS AND HELP     *   FILE 113
//*           IMPROVE PERFORMANCE.  WE HAVE INCLUDED THE MEMBERS    *   FILE 113
//*           AND JOBSTREAMS WE USED FOR THIS ACTIVITY ON FILES     *   FILE 113
//*           113 AND 114 OF THIS TAPE.                             *   FILE 113
//*           FILE 115 OF THIS TAPE CONTAINS THE SMPSCAN SOURCE     *   FILE 113
//*           WHICH IS WRITTEN IN PL/I OPTIMIZING COMPILER CODE.    *   FILE 113
//*           THIS FILE IS IN IEBUPDTE SYSIN FORMAT AND CONTAINS    *   FILE 113
//*           THE FOLLOWING :                                       *   FILE 113
//*                                                                 *   FILE 113
//*      $$$DOC      DOCUMENTATION MEMBER                           *   FILE 113
//*      SMPLGBL     SAMPLE JOB TO LIST GLOBAL ZONE FOR INPUT       *   FILE 113
//*      SMPL220     SAMPLE JOB TO LIST DLIB   ZONE FOR INPUT       *   FILE 113
//*      SMPLTMA     SAMPLE JOB TO LIST TARGET ZONE FOR INPUT       *   FILE 113
//*      SMPLPKA     SAMPLE JOB TO LIST TARGET ZONE FOR INPUT       *   FILE 113
//*      SMPSBTAM    SAMPLE JOB TO LOCATE BTAM ELEMENTS             *   FILE 113
//*      SMPSCLUP    SAMPLE JOB TO LOCATE LPALIB VSCR DELETES       *   FILE 113
//*      SMPSINFL    SAMPLE JOB TO LOCATE LMOD DOWN-LEVELING        *   FILE 113
//*      SMPSLPA2    SAMPLE JOB TO LOCATE 2-SYSLIB LPALIB LMODS     *   FILE 113
//*      SMPSTCAM    SAMPLE JOB TO LOCATE TCAM ELEMENTS             *   FILE 113
//*      SMPSCAN     SAMPLE CATALOGED PROCEDURE FOR SMPSCAN         *   FILE 113
//*                                                                 *   FILE 113
//*******************************************************************   FILE 113
//*                                                                 *   FILE 113
//*>>>>>>>>>>>>>>C U I C   D I S C L A I M E R<<<<<<<<<<<<<<<<<<<<<<*   FILE 113
//*                                                                 *   FILE 113
//*******************************************************************   FILE 113
//*            THE INFORMATION OR MATERIAL BEING PROVIDED           *   FILE 113
//*      BY COMMERCIAL UNION INSURANCE COMPANY (CUIC),              *   FILE 113
//*      WHETHER IN HARD COPY OR MACHINE READABLE FORM,             *   FILE 113
//*      HAS BEEN DEVELOPED BY CUIC FOR ITS OWN PURPOSE             *   FILE 113
//*      AND FOR USE ON ITS OWN EQUIPMENT AND WITHIN ITS            *   FILE 113
//*      OWN DATA PROCESSING SYSTEM.  CUIC MAKES NO                 *   FILE 113
//*      REPRESENTATIONS OR WARRANTIES WHATSOEVER WITH              *   FILE 113
//*      RESPECT TO THE INFORMATION OR MATERIAL FURNISHED           *   FILE 113
//*      HEREUNDER, EXPRESSED OR IMPLIED, INCLUDING BUT             *   FILE 113
//*      NOT LIMITED TO ANY REPRESENTATION OR WARRANTY OF           *   FILE 113
//*      MERCHANTABILITY OR FITNESS FOR ANY PARTICULAR USE          *   FILE 113
//*      OR PURPOSE OR THAT THE USE OF THE INFORMATION OR           *   FILE 113
//*      MATERIAL WILL NOT INFRINGE ANY PATENT, COPYRIGHT,          *   FILE 113
//*      TRADEMARK, OR OTHER PROPRIETARY INTEREST.  YOU             *   FILE 113
//*      ARE, THEREFORE, ACCEPTING THIS INFORMATION OR              *   FILE 113
//*      MATERIAL ON AN "AS IS" BASIS AND WILL BE USING IT          *   FILE 113
//*      AT YOUR OWN RISK.  NEITHER CUIC NOR ANY OF ITS             *   FILE 113
//*      AFFILIATES SHALL BE LIABLE WITH RESPECT TO ANY             *   FILE 113
//*      CLAIM, ACTION, OR DEMAND BY ANY USER OR OTHER              *   FILE 113
//*      PARTY (INCLUDING ANY CLAIM, ACTION, OR DEMAND FOR          *   FILE 113
//*      CONSEQUENTIAL DAMAGES EVEN IF CUIC HAS BEEN                *   FILE 113
//*      ADVISED OF THE POSSIBILITY OF SUCH DAMAGES)                *   FILE 113
//*      ARISING FROM THE USE OF THE INFORMATION OR THE             *   FILE 113
//*      MATERIALS AND CONCEPTS RELATED THERETO.                    *   FILE 113
//*      FURTHERMORE, CUIC WILL NOT MAINTAIN, CORRECT, OR           *   FILE 113
//*      UPDATE THIS INFORMATION OR MATERIAL IN THE                 *   FILE 113
//*      FUTURE.                                                    *   FILE 113
//*                                              01/26/83           *   FILE 113
//*******************************************************************   FILE 113
//*                                                                 *   FILE 113
```
