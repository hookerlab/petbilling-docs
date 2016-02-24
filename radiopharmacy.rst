Radiopharmacy
=============

This describes the use of the tool for our radiopharmacy.

.. Warning::
   **Should you use the web form?** You should only fill out this form for chemicals that were both **produced** in the radiopharmacy and were **not** handed over to Grae. If it was given to Grae, you have to do nothing in the web.

.. Note::
   Before starting you need to have all the data for the product you want to enter. Data for a product can only added if it is complete.

Meaning of the diffferent fields
--------------------------------

- *project code* : the three-letter code for the project. The code must exist in our database or the entry won't be processed. You should get this for the researcher that requested the dose.
- *production date* : the date where the dose was produced.
- *radiotracer type*: which can be a isotope or a compound. It must be chosen from what is avaliable in the database.
- *batch number*: a number labelling the batch for the product you made. If the batch number is ``n``, means this is the ``n-th`` batch of this product during that day. The batch number is used to assign automatically the Rx number for the product. For example, if today is February, 23rd, 2016, you're making the third batch of ``Ga68-Dota-toc``, you pick batch number equal to ``3`` and the Rx number would be ``160223-DTC03``.
- *starting activity*: the starting activity in mCi.
- *time*: time at which the starting activity was measured.
- *synthesis OK*: wheter the synthesis was sucessful (for compounds only).
- *quality control OK*: wheter the quality control passed (for compounds only).
- *comments*: write here anything relevant to the product you made. Sometimes the application adds some comments, so you don't have to repeat common comments (see `FAQs`_.)

What is a compound and what is an isotope
-----------------------------------------

The difference between isotopes and compounds is that compounds require a synthesis and a quality control. The fees charged are different too.

.. Note::
   It's important that you choose the right compound even if many are charged the same. The compound has information about the isotope on it and we use this to calculate activities for both nuclear safety and image analysis.

Generic compounds
-----------------

Generic compounds are compounds that are not in the database because they are still in development or they will be used only a few times. When you make one of these compounds, you should choose ``C11-Generic`` or ``F18-Generic``, depending on the isotope used. When you do that a new box will pop out so you can enter a (possible made-up) name for the compound. Also, a comment will be automatically added to the database, so you don't have to type this information in the comment field.

If you are releasing this to Grae, you would be passing a paper release form. In this release form, you should use an Rx number like ``160223-01C11GEN``, instead of ``160223-01BEX``, and then add a note with the actual name of the compound.

How the money is charged
------------------------

The fees for the different compounds are charged automatically when you fill out the form. You don't have to do anything extra. In general, the project code would be used to choose the proper funding and the amount would be determined from the data you entered.

If you're making a compound and the synthesis or the quality control failed, you should complete the web form anyway, choosing the proper options for the `Syntheis Ok` and `Quality Control OK` fields. The fees charged would be automatically voided and a comment would be added explaining why.

FAQs
----

**The code I got from the researcher is not valid**
You should go back to the researcher and ask for a valid code. Don't enter valid code from another project: this other project would be automaticallly billed!

**Which are the project codes for routinary taks in the radiopharmacy?**
There are some special project codes for internal tasks:

+------------+--------------------------------------------+
| Code       | Use                                        |
+============+============================================+
| cfc        | Conditioning for cyclotron                 |
+------------+--------------------------------------------+
| cdr        | Cyclotron Development Run                  |
+------------+--------------------------------------------+
| rpt        | Cyclotron Radiotracer Practice or Training |
+------------+--------------------------------------------+

**I made a compound but it's not in the database** If the compound is a one-time thing, you should choose the `Generic compounds`_ associated to the isotope you used. For example, if you made something with C11, you should choose C11-Generic as compound. If the compound is something you do often, you should add it to the database (coming soon).

**I made a mistake and entered some wrong data** Most of the times the form will catch the mistake and won't let you add the wrong data. If you realize the data is wrong and have clicked the submit button, you have the chance to fix it in the confirmation page. Edit the corresponding field there or just go back to the original form and fix it there. If you confirmed the data and realized later that was wrong, you should contact Ivan or Paul.

**What is added to my comments?** If the synthesis or the quality control for a compound are not OK, a comment saying that is automatically added. Feel free to write more if you feel so. (You won't see the automatic comment in the box, it's added at the end of the submission process.)
