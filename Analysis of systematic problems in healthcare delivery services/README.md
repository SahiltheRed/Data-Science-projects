# Data-Science-projects
Learning and developing my knowledge and understanding of data science

Project 3: Analysis of systematic problems in healthcare delivery services

A healthcare program, DevHealthOrg, uses biometrics to ensure the unique identity of its beneficiaries. They
have 3 databases users.txt, areas.csv, and visits.csv that correspond to a project in the region of
Syldavia.

users.txt contains information about the users in DevHealthOrg (community health workers), and the
beneficiaries who are assigned to them. Format for each line:
UserID: BeneficiaryID, BeneficiaryID, BeneficiaryID...

areas.csv contains information regarding where the beneficiaries were registered. Format for each row:
BeneficiaryID,DistrictID.

visits.csv contains a row every time a user met a beneficiary and delivered healthcare services. Format
for each row: Date,Type, BeneficiaryID. Type denotes whether or not the meeting happened in
the beneficiary’s house (Home) or at a healthcare clinic (Clinic), and BeneficiaryID denotes which
beneficiary was receiving healthcare. Date denotes when the beneficiary was visited

DevHealthOrg wants to diagnose any systematic problems in healthcare delivery services, and needs your help
as a data scientist. Write a script (in a language of your choice) to analyse the data and provide the insights
they are after.

Note that each user provides healthcare services to the beneficiaries that they are assigned, and all users are
expected to work the same number of hours. For the purposes of this task, a good proxy for “amount of
healthcare being received” for a given beneficiary is the number of meetings between a beneficiary and a user
(irrespective of whether they happened at a clinic or at home). Besides this, feel free to make assumptions
about the data and the program as long as you state them explicitly.

Please provide
  (A) which districts have beneficiaries that are not receiving sufficient amounts of healthcare
  (B) your source code to answer (A)
  (C) any assumptions you make
  (D) possible explanations for why you see what you see, and potential recommendations to the program

