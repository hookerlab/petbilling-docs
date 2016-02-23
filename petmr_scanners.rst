PET/MR scanners
===============

This describes the use of the tool for our scanners in Bay 6 and 7.

.. Warning::
   **Should you use this form?** Yes, you should always fill out a form in the website for any type of scan (human, animal, or phantom) performed in Bay 6 or Bay 7.

.. Note::
   Before starting you need to have all the data for the product you want to enter. Data for a product can only added if it is complete.

Meaning of the diffferent fields
--------------------------------

- *project code* : the three-letter code for the project. The code must exist in our database or the entry won't be processed. You should get this for the researcher that requested the dose.
- *scan date* : the date where the scan was performed.
- *is external?*: whether the dose comes from our radiopharmacy or was purchased,
- *Rx number*: a number labelling the dose. If the dose was made in our radiopharmacy, it would be something like  ``160223-DTC03`` for a dose of ``Ga68-Dota-toc`` made on February, 23rd, 2016. Otherwise, it would be whatever Rx number was provided by the dose manufacturer.

.. Note::
   If the dose comes from our radiopharmacy, you should have to fill out some information about its activity. All this data is in the release form you got from the radiopharmcy.

What is an external dose
------------------------

External doses are purchased instead of being made by Judit's team. Because we don't need to track the activity at production time for nuclear safety reasons, the only thing you need to enter is the compound name and the Rx number for the dose.

.. Note::
   It's important that you choose the right compound even if many are charged the same. The compound has information about the isotope on it and we use this to calculate activities for image analysis.

Completion codes for scans
--------------------------

All scans have a completion status. We use the completion status to charge for the scan. You choose the completion status in two steps. First you need to answer if the scan was completed normally. A scan is completed normally if it has data for the whole duration of the scan. If the scan has not completed normally, you should choose one of several statuses from this list:

+------------------------------+-----------------------------------------------------------------------------------------------+
| Status                       | Meaning                                                                                       |
+==============================+===============================================================================================+
| Subject no show              | Subject didn't show and no procedure was done                                                 |
+------------------------------+-----------------------------------------------------------------------------------------------+
| Subject showed, no injection | Subject showed, some procedure may be done, but subject wasn't injected                       |
+------------------------------+-----------------------------------------------------------------------------------------------+
| Subject injected, no scan    | Subject was injected, some other procedures may be done, but no scan session was started      |
+------------------------------+-----------------------------------------------------------------------------------------------+
| Subject injected, bad scan   | Subject was injected, some other procedures may be done, a scan session started, but there    |
|                              | is no scan data or scan data is useless                                                       |
+------------------------------+-----------------------------------------------------------------------------------------------+
| Partial scan                 | Subject was injected, some other procedures may be done, there is useful scan data, but is    |
|                              | not fully and normally complete                                                               |
+------------------------------+-----------------------------------------------------------------------------------------------+
| Complete scan                | Scan completed fully and normally                                                             |
+------------------------------+-----------------------------------------------------------------------------------------------+


How the money is charged
------------------------

The fees for the different procedures are charged automatically when you fill out the form. You don't have to do anything extra. In general, the project code would be used to choose the proper funding and the amount would be determined from the data you entered.

The scanner fee is charged if a session was started in the scanner. The fee for the dose is charged automatically according to the compound used and whether it was produced in-house or purchased fomra vendor. Additional procedures are charged if you click on the correspoding box.

FAQs
----

**The code I got from the researcher is not valid**
You should go back to the researcher and ask for a valid code. Don't enter valid code from another project: this other project would be automaticallly billed!

**I made a mistake and entered some wrong data** Most of the times the form could catch the mistake and won't let you add the wrong data. If you realize the data is wrong and have clicked the submit button, you have the chance to fix it in the confirmation page. Edit the corresponding field there or just go back to the original form and fix it there. If you confirmed the data and realize later that was wrong, you should contact Ivan or Paul.

**Which is the difference between a "Subject injected, no scan" and "Subject injected bad scan"?** In none of them there'll data uploaded to Bourget and in both of them you may charge for other procedures (such as a pregnancy test). The difference is that for "Subject injected, no scan" you didn't start a session on the scanner and in "Subject injected, bad scan" you did. The researcher would be charged the scan fee in the second case, but not in the first.

**Which is the difference between a "Subject injected, bad scan" and "Subject injected bad scan"?** In both of them you started a session in the scanner (so the researcher gets charged the PET/MR fee) and you may charge for other procedures (such as a pregnancy test). The difference is that for "Subject injected, bad scan" you don't upload the data to Bourget because is useless and the second you did upload the data. An example could be a patient leaving the scanner 5 minutes after the start of the session ("bad scan") versus a patient leaving the scanner 87 minutes into a 90-minute session (partial scan).

**Which is the difference between a "Partial scan" and "Complete scan"?** In both of them you started a session in the scanner (so the researcher gets charged the PET/MR fee) and you may charge for other procedures (such as a pregnancy test) and you uploaded data to Bourget. The form you have to fill is exactly the same too. The difference is that in the partial scan case you want to let know the researcher that the scan is not completed as in the IRB, so she may have to tweak her analysis to account for this fact. You could use this in cases were the scan is a bit shorter than scheduled, or maybe to note that the subject move too much at some point. It's mostly your decision: regarding this web application both are treated the same.
