# EDI-and-Sterling-Integrator-
EDI is a set of standardized formats for different types
business documents that allow otherwise incompatibel business
data processing system to exchange documents without manual 
intervention

Advantages of EDI:
-----------------
Less Human intervention
High Throughput
Few Errors
Ability to do just in time(JIT)
More security

Companies using EDI:
-------------------------
 Retail industry
 Banking 
 Healthcare
 Government sector

Different EDI Standard
---------------------------
Amercial National Standard Institure( ANSI X112 Commitee)
EDIFACT(EDI for administration and transport)
TDCC(Transportation Data Coordination committee)
VICS(Voluntary Inter industry communication standard)




Application Data----<----- Transalator-----<----EDI Data (inbound)

Application Data------>--- Transalator------->--EDI Data (outbound)

ANSI
------

ISA Interchange (headers)
  GS Function group (headers)
   ST Transaction  (headers)

   SE              (tailer)
   ST Transaction  (tailers)

   SE Transaction  (tailers)
  GE               (tailers)
IEA                (tailers)


EDIFACT Envelopes
-------------------

UNB Interchange (headers)
  UNG Function group (headers)
   UNH Message  (headers)

   UNT              (tailer)
   UNH Message   (tailers)

   UNT Message   (tailers)
  UNE               (tailers)
UNZ                 (tailers)

ISA (interchange control Header)
-----------------------------------
**Total length of ISA IS 106 Bytes and 16 elements

IEA (Interchange control trailer)
-------------------------------------
*Total lenght of IEA is 8 bytes and 2 elements


GS(Functional Group Headers)
-----------------------------------------
Total length of gs IS variable length and 8 elements 


 ST Transaction  (Transaction set tailers)
 ---------------------------------------------
  Total length variable lenth and 2 elements








  
