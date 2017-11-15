
==========================================
Implemented corrections checking procedure
==========================================

The goal of the PubMed process is to take articles through all the stages of the process as quickly as possible. Therefore, any delays at one step or another cause overall delay in availability of the article for archiving.

Implemented corrections checking is important step in overall process and it should be delivered quickly and efficiently.

It is important for team members to adhere to the procedures outlined below and follow them to the point.

It is important task of a manager to monitor and resolve situations when article is "stuck" at certain point.

Instructions for team member
============================

The tasks of the team member are composed of 2 major steps: 

- check whether corrections have been implemented by Production team in full (and if so, update Production Spreadsheet accordingly) and 
- if corrections have not been implemented (in full), send email to Production team asking to implemented missed corrections (and update Production sheet accordingly)

1. Go to the "`Implemented Corrections Dashboard`_". There you can see all the articles for which corrections have been implemented. Use this Dashboard as a work list. Process PIIs one by one.

2. Open the Production Mailbox (production@oncotarget.com)

3. Copy PII from the dashbord and search it in the Production Mailbox for all emails containing pii number in the subject line. There can be emails to Production Team as well as to the author(s) of the article. 

In general there can be 3 situations you would need to deal with: |br|
a. :ref:`there was no communication with author<no_communication_with_author>` |br|
b. :ref:`there was communication with author and author have not replied yet<communication_but_not_replied_yet>` |br|
c. :ref:`there was comminication with author and author has already replied<communication_and_reply>`

.. _no_communication_with_author:
a. There was no communication with author

How to find out: there is "N" in `Author response required?` column.

What to do:

Take a look at the `Date correx last reviewed` column in Production Spreadsheet to find out whether article has been checked for implemented corrections before. If it was, check corrections wich are older than that date. Otherwise check all whether all corrections related to the article have been implemented.

If all corrections have been implemented, then :ref:`go here<implemented_no_communication>`.
If all or certain corrections have not been implemented, then :ref:`go here<not_implemented>`.

.. _communication_but_not_replied_yet:
b. There was communication with author and author have not replied yet.

How to find out: there is "Y" in `Author response required?` column and `Response to auth correx forwarded to production` column is empty.

What to do:

Take a look at the `Date correx last reviewed` column in Production Spreadsheet to find out whether article has been checked for implemented corrections before. If it was, check corrections wich are older than that date. Otherwise check all whether all corrections related to the article have been implemented.

If all corrections have been implemented, then :ref:`go here<implemented_not_replied>`.
If all or certain corrections have not been implemented, then :ref:`go here<not_implemented>`.

.. _communication_and_reply:
c. there was comminication with author and author has already replied.

How to find out: there is "Y" in `Author response required?` column and `Response to auth correx forwarded to production` column has a date.

Take a look at the `Date correx last reviewed` column in Production Spreadsheet to find out whether article has been checked for implemented corrections before. If it was, check corrections wich are older than that date. Otherwise check all whether all corrections related to the article have been implemented.

If all corrections have been implemented, then :ref:`go here<implemented_and_replied>`.
If all or certain corrections have not been implemented, then :ref:`go here<not_implemented>`.

.. _implemented_no_communication:
**All corrections implemented, no communication with author***

- Go to Production Spreadsheet and update column "Date correx last reviewed" with the date when you checked the pii and put "Y" in column "Corrections approved? (Y or N)"

.. _implemented_not_replied:
***All corrections implemented, author has not replied yet***

- Go to Production Spreadsheet and update column `Date correx last reviewed` with the date when you checked the pii.
- There are 2 columns named `Corrections approved? (Y or N)`, put "N" in the empty column and add note "corrx approved, but awaiting auth. resp. + add current date" to the *rightmost* "Approval Notes" column . If both `Corrections approved? (Y or N)` contain values (i.e. "N") then just append *rightmost* `Approval Notes` column with "corrx approved, but awaiting auth. resp. + add current date"

.. _implemented_and_replied:
***All corrections implemented, author replied***

- Search for the email from PubMed team member to Production team containing corrections related to author's response.

- If you do *not* find that email, treat this paper as "All corrections implemented, author has not replied yet"

- Double cheeck that corrections related to author response have been implemented. 

- If implemented go to `All corrections implemented, no communication with author`, otherwise go to "Corrections not implemented".
 
.. _not_implemented:
***Corrections not implemented***

- Send reply to the Production team with the list of corrections which have not been implemented.
- Go to Production Spreadsheet and update column `Date correx last reviewed` with the date when you checked the pii.
- There are 2 columns named `Corrections approved? (Y or N)`, put "N" in the empty column and add note "missed corrx + add current date" to the *rightmost* "Approval Notes" column . If both `Corrections approved? (Y or N)` contain values (i.e. "N") then just append *rightmost* `Approval Notes` column with "missed corrx + add current date"

.. _Implemented Corrections Dashboard: https://docs.google.com/spreadsheets/d/1Wqrf_ysPZFPs4p5B5d-djR5zbaZjoiimxOCMCY1LrHI/edit#gid=199064208


.. |br| raw:: html

   <br />
