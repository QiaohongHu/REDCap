# CAPMC Recruitment Tracking Project in REDCap

kai.zheng@uci.edu

<B>Mar 2, 2018</B>

(1) On "Form 1. Profile & Clinic Appointment," added two new questions:

Do not use. Duplicated record. Information about this participant is recorded under another Study ID.

Do not contact. Deceased or declined to receive future study communications.

<B>Dec 11, 2017</B>

(1) In question "Agreed to participate?" on "Form 4. Decision", added a new response option:

not_uci_patient, Not UCI Health patient

(2) As a result, modified the filter logics for the following Reports:

Contact #1 Due<BR>
Contact #2 Due<BR>
Contact #3 Due<BR>
Contact #4 Due

(3) Modified the filter logic for the following Reports to improve performance of the Dashboard (by adding date constraints to reduce unnecessary API data pull):

Admin: Dashboard<BR>
Admin: Dashboard (R.S.)<BR>
Admin: Dashboard (Completed)<BR>

(4) Uploaded two zip files:

All_of_Us_Email.zip: Containing code for sending weekly recruitment emails. Sending results are manually imported into REDCap.

All_of_Us_Thank_You_Email.zip: Containing code for sending daily thank-you note for those who completed the study. Sending results are automatically updated in REDCap via API (recorded in "Form 11. Admin").

<B>Dec 5, 2017</B>

(1) Minor revision to the filter of "Report 4. Volunteers Not Yet Enrolled".

(2) Added a new question on "Form 7. Meeting Results" (meeting_ehr_consent) and "Form 8. Rescheduled Meetings" (rescheduled_meeting_ehr_consent):

<I>EHR consent provided in Patient Portal?<BR>
yes, Yes<BR>
declined, No, declined to provide<BR>
will_provide, Not yet, but will provide it<BR>
other, Other (specify in notes)</I>

(3) On "Form 1. Profile & Clinic Appointment", revised the label "Date added" to "Date added or updated". Variable name remains unchanged ("date_added").

<B>Nov 14, 2017</B>

Added specifications for Reports.

(1) "Reports - Filters.txt" contains definitions for filters of each report.

(2) "Reports - Data Fields, Live Filters, Order by.zip" contains screenshots which show data fields included in each report and Live Filter(s) and the Order By clause. 

<B>Nov 2, 2017</B>

Major changes include:

(1) On "Form 1. Profile & Clinic Appointment," added "Volunteered to participate?" This flag indicates if the patient has already volunteered to participate via other channels (e.g. by responding to the recruitment sent through the employee mailing list).

(2) On "Form 5. Meeting Planning" and "Form 8. Rescheduled Meetings," added a new question "Participant needs assistance in completing consent and/or PPI on site?"

(3) On "Form 7. Meeting Results" and "Form 8. Rescheduled Meetings," added a new response option "Canceled and withdrawn (specify withdrawing information on Form 10)" to the question "Meeting took place?"

(4) On "Form 7. Meeting Results," added a new question "Meeting rescheduled or canceled on the same day of the appointment?".

(5) On "Form 9. Gift Card," added a new question "If there are further study activities of All of Us, is participant willing to continue to be involved?"

<B>Oct 20, 2017</B>

The .xml file contains project export in the CDISC ODM format. 

The .csv file contains data dictionary.

Major changes made recently:

(1) Added several new response options in "Contact outcomes" and "Meeting outcomes".

(2) Added several new response options in "Reasons for declining" and "Reasons for withdrawing"

(3) Added a new form "Rescheduled Meetings" and made it a repeatable instrument.

(4) Numerous UI and wording improvements.
