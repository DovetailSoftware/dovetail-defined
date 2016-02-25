# Clarify Client Forms

*   [Custom](#custom)
*   [Baseline](#baseline)

<a id="custom" name="custom"></a>

## Custom Forms

<pre>   A) Form ID numbers will be used in the range: 1900-2500\. Each
       customization will be assigned an (initial) range of 5 or 10 forms.
       If more are needed, they will be assigned as appropriate. The
       following ranges have been assigned:

      1) Queue groups            : 1900-1909
      2) Survey customization    : 1910-1919
      3) Contact merge           : 1920-1929
      4) Source Control Interface: 1930-1949
      5) FC Internal             : 1950-1969
         A) Localized String Form: 1950
         B) Locale Selection Form: 1951
         C) List Maintenance Form: 1952
         D) List Select Form     : 1953
         E) Config Item GUI      : 1954
         F) String DB GUI        : 1955
         G) Date/Time Dialog     : 1956
      6) Logistics Enhancements  : 1970-1989
         A) Select FIFO Cost       1970
         B) FIFO Cost              1971
         C) Recalculate Inventory  1972
             Summation
         D) Select Container       1973
         E) Select Batch           1974
         F) Edit Batch             1975
         G) Work order tab for 411 1976
         H) Work order tab for 420 1977
         I) Batch - General tab    1980
         J) Batch - Part Req tab   1981
         K) Batch - Shipping tab   1982
      7) RPA                     : 1990-1991
         A) Page Monitor           1990
         B) Page Request           1991
      8) PCAL                    : 1992-1999
         A) Zipcode Select         1992
         B) Street Address Lookup  1993
      9) AMI                     : 2000-2009
         A) AMI Systems            2000
         B) AMI Objects            2001
         C) AMI Fields             2002
         D) AMI Attribute history  2003
         E) AMI Part Details       2004
         F) AMI Reconcile Tab      2005
         G) AMI Related Site Parts 2006
         H) AMI Edit Attributes    2007
         I) AMI Part Alias Form    2008
     10) Flexible Pricing        : 2010-2014
     11) Data Restriction        : 2020-2024
     12) SLAM                    : 2030-2034
         A) Monitor Form           2030
         B) Config Form            2031
     13) Administrator Toolkit   : 2200-2209
         A) Path Editor            2200
         B) Query Property Editor  2203
         C) Activity Log Editor    2204
         D) Business Rule Editor   2205
         E) Auto-Dest Editor       2206
     14) Query Anything            2210-2224
     15) PO module               : 2225-2249
     16) Recently Open Objects   : 2250
     17) Super Email Clerk       : 2251-2255
     18) Consultant Invoicer     : 2260
     19) Employee Manager        : 2265-2269
     20) ActiveX                 : 2270
     21) Employee Manager Part 2 : 2271-2275
     22) DIFOC                   : 2276-2279
     22) Product Email Tool      : 3559
     23) Interface Builder       : 3560-3585
     24) AWE                     : 3586-3594
     25) Flashes Anywhere        : 2800-2824
     26) Enhanced Emailer    : 2825 - 2835
         A) Message Tab            2825
         B) Commitments Tab        2826
         C) Attachments Tab        2827
         D) Main Email form        2828
         E) Address Book Form      2829
     27) Clarify Explorer        : 2840 - 2859
     28) Clarify Explorer        : 2860 - 2865
     29) fcClient                : 4600-4700
     30) DART                    : 4250-4259
     31) CLAMM                   : 4260-4269

</pre>

<a id="baseline" name="baseline"></a>

## Baseline Forms

<pre>Each time a customization "touches" an existing form, that information should be recorded here:

      Customization     Form Number              Description
      -------------------------------------------------------------
      RES               321                      Added data restriction filter
      RES               611                      Added data restriction filter
      RES               707                      Added data restriction filter
      RES               717                      Added data restriction filter
      RES               728                      Added data restriction filter
      RES               11300                    Added data restriction filter
      Consultant Inv    411                      Added labor rate, time & expense,
                                                 & invoice buttons
      Consultant Inv    420                      Added labor rate, time & expense,
                                                 & invoice buttons
      Consultant Inv    717                      Added travel rate multiplier text box
      ZRD               505                      Added zipcode lookup
      (Zipcode Reverse Directory)
      ZRD               706                      Added zipcode lookup
      ZRD               769                      Added zipcode lookup
      ZRD              9673                      Added zipcode lookup
      PCAL              505                      Added street address validation
      PCAL              534                      Added street address validation
      PCAL              706                      Added street address validation
      PCAL              769                      Added street address validation
      PCAL             9673                      Added street address validation
      EE                391                      now uses enhanced email form to display
                                                 emails
      EE                498                      added message to display based
                                                 on commitment from email
      fcClient          743                      Added "Web Cmds..." button

</pre>
