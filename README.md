# TrekBuddy
CW QRP transceiver 

There is no perfect transceiver for an amateur radio, otherwise we should have as many radio models as amateurs around the world. Also electronic part becomes more and more hard to build for elmers in their workshops. I would to create device that maybe is not the simplest one but gives a lot of flexibility, software is open and well-described, which makes it easy to adapt this project to your own needs even for non-programmers.

Assumtions : 
  1. Modern receiver - QCX style
      a. most of procects base on NE602 IC that a not good choice in modern days
      b. QCX lack of AGC - SSM2165 and AGC control ciquit idea  
      c. Low pass filter MAX7400
  2. PA in D class - like in QCX/uSDX - DL2MAN board 5 or 8 bands as reference ??? 
  3. 5 bands 80-60-40-30-20 - or any other
  4. Good keyer
  5. Audio recorder onboard - often we dont have anything to make note in field or we want audio record to our archive wiht MKRZERO this should be easy to implement
  6. Optional GPS - rof time synchronisation and position readout (POTA/SOTA)
  7. Digital part can be used with any oter project
  8. Some popular easy tu by enclousure (moct projects do not care about this part)
  9. Manipulation elements (buttons. vfo/multifunction knob) should have low profile to avoid damage when putting them in and out from pocket
  10. SSB reception
  11. This should be as number 1 - software fully avialable as OpenSource to give opportunity to enable the further development of the project ar align to own needs

Milestones
  1. Use QCX as base, remove original uC and use connect TrekBuddy instead
  2. Make receiver operational - sytheiser should give 2 signals 90 degree shifted
  3. Make audio recorder operational
  3. Make TX operation with stright key
  4. Add DL2MAN board, add 5 band capability and make them operational
  5. Make keyer part operational - as minimum IAMBIC B
  6. GPS capability - to synchronize time and get position/GRID for SOTA/POTA/WWFF activations
