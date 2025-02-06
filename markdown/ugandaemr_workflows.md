# UgandaEMR Mind Map

## Landing Page

### Reception

#### Appointments #Not Working #Concept Created
	There is need to extend appointment privillages to Receptionist
- View Appointment List #Working
- View Appointment Calender #Working
- Create Patient Appointment #Working
	- Location
	- Service
	- Appointment Type
	- Is Recurring
	- Date of appointment
	- Time of appointment
	- Duration of Appointment
	- Date Appointment issued
	- Provider to see
	- Notes
- No. Of Expected Appointments

#### Manage Patient Details #Working
- Register Patient #Working
	- Names #Working
		- Surname
		- Middle Name
This is regarded as given name
		- Firstname
These are regaded as given name
	- Birth Date #Working
	- Fingerprint #Concept Not Created
	- Relationship #Working
		- Relationship Type
			- Doctor
			- Patient
			- Parent
			- Sibling
			- Child
			- Aunt/Uncle
			- Nephew/Niece
			- Supervisee
			- Supervior
			- Spouse
		- Full Names
	- Identifiers #Working
		- National ID #Working
		- Systrem ID (OpenMRS) #Working
		- Facility ID #Concept Not Created
	- Demographics #Working
		- Marital status #Working
		- Nationality #Working
		- Occupation #Working
		- Education Level #Working
	- Contact information #Working
		- Telephone number #Not Working
		- Email #Working
		- Locator information #Concept Not Created
		- Alternative Phone Number #Working
	- Next Of Kin #Working
		- Name #Working
		- Phone Number #Working
- Search Patient
	- Search Local EMR  #Working
		- Identifiers
		- Names
	- Search National MPI #Working
		- Identifier
		- Names
			- Firstname
			- Last Name
			- Other name
		- Gender
		- Date of birth
		- Country
	- Search Facility SHR #Working
		- Identifier
		- Names
			- Firstname
			- Last Name
			- Other name
		- Gender
		- Date of birth
		- Country
- Edit Patient #Working
When editing, the  Information is the same as registration

#### Queues (Reception) #Working
- View Queue KPI #Working
- Checkin Patient #Working
- View Queue Screen #Working
- No. of Checkedin Patients

### Triage

#### View Patient Dashboard
- [ ] Capture Vitals #Working
- [ ] Capture Biomentrics #Working
- [ ] Send Patient to next service point #Working
This button should only appear when Patient is in a queue of the clinician. 

#### Queues
- View Pending in Queue
	- [ ] Pick Patient #Working
	- [ ] Navigate to Patient Dashboard
- View Completed Patients #Working
	- [ ] Navigate to Patient Dashbord #Working
- [ ] View Triage Statistics #Working

### Provider #Not Working #Concept Created
	The Providers Include
	- Clinicians
	- Doctors
	- Nurses
	- Councilors
	
	At the moment, the provider can see more than what is required of them,
	They can see 
	- Reception
	- Data Visualizer
	- Triage
	-Clinical Room
	- Laboratory 
	- Pharmacy
	
	They should only see Clinical room. 

#### Queues
- View Pending Pendtisn
- View Completed Patients
- View Provider Queue Statistics
- Pick patient

#### View Patient Dashboard #Working
- Clinical Views
This is not yet available. 
	- HIV Program
		- HIV Prevention Services 
			- HTS
			- Prep Care Card
			- PEP Care Card
		- HIV Care and treatment
			- Summary Page (Enrollment)
				- Enrolment into HIV care #Concept Not Created
New concept separate from Date of registration at this site. 
Interpreted as the date when patient enrolled into care. It could be the same as the registration at this site or different. 
				- Date of registration at this site #Concept Created #Working
Encounter Date of the Summary Page
				- Cofirmatory Testing #Concept Not Created
					- Test Type (99080) #Concept Created #Working
						- Ab (99079) #Concept Created #Working
AB - Antibody
						- PCR (99080) #Concept Created #Working
					- Date verification HIV test (168120) #Concept Created #Working
					- Where (99081) #Concept Created #Working
Where was test done from
				- In School (5629) #Concept Not Created
					- Yes (1065) #Concept Created #Working
					- No 1066 #Concept Created #Working
				- Special Cateory (165169) #Concept Created #Working
					- Migrant workers (165126) #Concept Created #Working
					- PWID (160666) #Concept Created #Working
People Who Inject Drugs
					- Migrant Worker (165126) #Concept Created #Working
					- Prisoner (162277) #Concept Created #Working
					- Refugee (165127) #Concept Created #Working
					- AGYW (165132) #Concept Created #Working
					- Fisher folk ()159674 #Concept Created #Working
					- Long-distance driver (162198) #Concept Created #Working
					- Uniformed forces (165125) #Concept Created #Working
					- Non Injecting drug user #Concept Not Created
					- YAPS #Concept Not Created
Adolosent and Young Persons 
				- Care entry point (90200) #Concept Created #Working
					- eMTCT (90012) #Concept Created #Working
					- Outreach (90019) #Concept Not Created
The Current one points to IDU reachout. might consider creating one and assigning it to that. 
					- TB (90016) #Concept Created #Working
					- Out-patient (90013) #Concept Created #Working
					- YCC (99593) #Concept Created #Working
					- STI (90015) #Concept Created #Working
					- SMC (99610) #Concept Created #Working
					- Inpatient (90018) #Concept Created #Working
					- KP Clinic #Concept Not Created
				- Treatment Interruptions (165232) #Concept Created #Working
The previous inturruption was built towards ART Interruptions. There is  a need of a redesign
					- Treatment Type (165228) #Concept Not Created #Working
						- ART (99132) #Concept Created #Working
						- TPT (165225) #Concept Created #Working
						- Fluconazole (747) #Concept Created #Working
						- TB Drug (58) #Concept Created #Working
					- Interruption (165229) #Concept Created #Working
						- Stopped (1363) #Concept Created #Working
						- Lost (99133) #Concept Created
Lost is the same as missed drug pickup appointment. Might need consider changing to Lost
					- Date of Interruption (165230) #Concept Created #Working
					- Restarted/Reactivated #Concept Not Created
						- Yes (1065) #Concept Created
						- Not (1066) #Concept Created
					- Restart Date (160738) #Concept Created #Working
				- Treatment outcome #Concept Not Created
					- Transfer out
Its now part of the encounter
						- Date of Transfer out (99165)
						- Transfered to (90211)
					- Lost to follow (Drop) (99167)
						- Lost to follow date (90209)  #Concept Created #Working
						- Lost to Follow (5240) #Concept Created #Working
							- Yes (90003) #Concept Created #Working
Consider migrating all Yes to 1065
							- No (90004) #Concept Created #Working
Consider migrating all No to 1066
					- Dead
Part of person Object
						- Cause of Death
							- Died of TB (58) #Concept Created #Working
							- Died of Cancer (116030) #Concept Created #Working
							- Died of Infectious disease other than TB (165374) #Concept Created #Working
							- Died of Non-infectious disease (165375) #Concept Created #Working
							- Died of Other NCDs #Concept Not Created
							- Died of Natural causes (165376) #Concept Created #Working
							- Died of Non Natural causes (165377) #Concept Created #Working
							- Died of ADR #Concept Not Created
							- Died of Unknown (90001) #Concept Created #Working
						- Death Date
Part of person object
				- Initial Regimen(99162)
Baseline Regimen
					- Baseline ARV Regimen (99061) #Concept Created #Working
					- Baseline ART Start Date (99161) #Concept Created #Working
					- Baseline weight (99069) #Concept Created #Working
					- Baseline Clinical Stage (99070) #Concept Created #Working
					- Baseline CD4 (99071) #Concept Created #Working
					- Baseline eMTCT #Concept Not Created
						- Pregnant (99072) #Concept Created
						- Lactating (99603) #Concept Created
						- Not Applicable (1175) #Concept Created
				- Transfer In Regimen (99065)
					- Transfer In Date (99160) #Concept Created #Working
					- ARV Regimen (99064) #Concept Created #Working
						- Other (90002) #Concept Created #Working
						- Specify (99269) #Concept Created #Working
					- Trasnfer in from (90206) #Concept Created #Working
				- Prior ARV/ART
					- Prior ART (99055)
						- Yes (90003)
						- No (90004)
					- Prior ART Set
						- Prior ART Type
							- PREP
							- PEP
							- Hep-B
							- PMTCT
							- ART 
When Patient only Had art and not from a transfer 
						- Duration in months
						- Priot ART Start Date
			- Family Tracking 
Encounter of Family Member
				- Family Member (99075) #Concept Created #Working
					- Name (99073) #Concept Created #Working
					- Relationship (164352) #Concept Created #Working
						- Spouse  (90288) #Concept Created #Working
						- Child (90280) #Concept Created #Working
						- Other Relative (5620) #Concept Created #Working
						- Other Sexual partner (165274) #Concept Created #Working
					- Age (99074) #Concept Created #Working
					- Age unit (99725) #Concept Created #Working
						- Years (1074) #Concept Created #Working
						- Months (99726) #Concept Created #Working
					- Is in EID Care (99881) #Concept Created #Working
						- Yes (90003) #Concept Created #Working
						- No (90004) #Concept Created #Working
					- HIV Status (165275) #Concept Created #Working
						- Positive (90166) #Concept Created #Working
						- Negative (90167) #Concept Created #Working
						- Unknown (90001) #Concept Created #Working
					- Is in HIV Care (90270) #Concept Created #Working
						- Yes (90003) #Concept Created #Working
						- No (90004) #Concept Created #Working
					- EID No. (90263) #Concept Created #Working
					- HIV Status Date (165276) #Concept Created #Working
					- Family Member Contact (159635) #Concept Created #Working
			- Treatment Regimen #Working
The Treatment Plan is an encounter That has all the details about patient regimen. 
				- Switch Regimen #Concept Not Created
Need to create a set for the switch
					- Previous Regimen (166039) #Concept Created
					- New Regimen (90315) #Concept Created
					- Switch Date #Concept Created
Encounter date when the switch happened
					- Regimen Line #Concept Created
Currently Program workflow. Should we consider moving it back to observation??
					- Reason for switching (90247) #Concept Created #Working
				- Substitution Regimen #Concept Not Created
Need to create a set for substitution. 
					- Previous Regimen (166039) #Concept Created
The regimen the person has been on 
					- New Regimen (90315) #Concept Created #Working
The regimen a person is switching to
					- Substitution Date #Concept Created #Working
The encounter Date when the substitution happened
					- Reason for Substitution (90246)  #Concept Created #Working
			- Clinical Assessment
This is the clinical assessment with ART Encounter
				- TPT #Concept Not Created
					- Start Date (165226) #Concept Created #Working
					- Completion Date (165227) #Concept Created #Working
					- Sides of TPT #Phasedout
					- TPT Status (165288) #Working
						- Eligible not Initiated #Concept Not Created
						- On TPT (90072) #Concept Created #Working
						- Defaulted (165307) #Concept Created #Working
						- Permanently Not Eligible #Concept Not Created
						- Completed (160035) #Concept Created #Working
						- Not Eligible (1364) #Not Working #Concept Created
					- TPT Drug Plan #Concept Created
						- 3HP (166907) #Concept Created #Working
3 month of Isoniazid + riphampicin, 1 pill once daily
						- 1HP #Concept Not Created
1 month of Isoniazid + riphampicin, 1 pill once daily
						- 6H #Concept Not Created
6 months of Isoniazid one pill daily
				- Appointment #Concept Not Created
					- Date of Appointment #Concept Created #Working
					- Reason for appointment #Concept Created #Working
						- ART Drug refill (164972) #Concept Created #Working
						- Lab Monitoring #Concept Not Created
						- PMTCT (90012)
						- Mental/Psychosocial Monitoring including IAC
							- IAC (163153) #Concept Created #Working
							- Mental (165264) #Not Working #Concept Created
						- Clinical Assessment (165284) #Concept Created #Working
						- TB Drug Refill (164971) #Concept Created #Working
						- EID (164974) #Concept Created #Working
						- Others (90002) #Concept Created #Working
							- Other Appointment Reason (164975) #Concept Created #Working
				- NCDs #Concept Not Created
					- HTN Status (198894) #Concept Created #Working
						- Normal Blood pressure (198885) #Concept Created #Working
Normal Blood pressure is BP<140/90 mmHg
						- Newly Diagnosed and on lifestyle modification (198886) #Concept Created #Working
with BP ≥140 or ≥ 90mmHg
						- Newly Diagnosed  and
						  on lifestyle modification & Medication (198887) #Concept Created #Working
with BP ≥140 or ≥ 90mmHg
						- Known Hypertensive, not controlled  and
						  on lifestyle modification & Medication (198889) #Concept Created #Working
BP ≥140 or ≥ 90mmHg
						- Known Hypertensive and Controlled and on lifestyle modification (198890) #Concept Created #Working
with BP<140/90mmHg
						- Known Hypertensive and Controlled and on
						  lifestyle modification & Medication (198891) #Concept Created #Working
with BP<140/90mmHg
						- Known Hypertensive but not on Treatment (198892) #Concept Created #Working
						- Hypertensive patient referred for further management (198893) #Concept Created #Working
					- Diabetes Mellitus Status (198900) #Concept Created #Working
						- No signs and symptoms (162848) #Concept Created #Working
Based on the Screening tool for Diabetes
						- Normal blood sugar (198895) #Concept Created #Working
FBS≤7.0mmol/126mg/dl or RBS≤11 mmol/200mg/dl)
						- Newly Diagnosed on lifestyle modification (198886) #Concept Created #Working
FBS>7.0mmol/126mg/dl or RBS>11 mmol/200mg/dl
						- Newly Diagnosed on medication and lifestyle modification (198887) #Concept Created #Working
FBS>7.0mmol/126mg/dl or RBS>11 mmol/200mg/dl
						- Known Diabetic and controlled  on medication and lifestyle modification (199031) #Concept Created #Working
FBS≤7.0mmol/126mg/dl or
RBS≤11 mmol/200mg/dl
						- Known Diabetic and not controlled on lifestyle modification  (198896) #Concept Created #Working
FBS>7.0mmol/126mg/dl or RBS>11 mmol/200mg/dl
						- Known Diabetic and not controlled on medication and lifestyle modification (198897) #Concept Created #Working
FBS>7.0mmol/126mg/dl or
RBS>11 mmol/200mg/dl
						- Known Diabetic and controlled  on lifestyle modification #Concept Not Created
FBS≤7.0mmol/126mg/dl or
RBS≤11 mmol/200mg/dl
						- Known Diabetic but not on Treatment (198898) #Concept Created #Working
						- Diabetic patient referred for further management (198899) #Concept Created #Working
					- Mental Health (MH) Status #Concept Not Created
						- MH-A/D (198879) #Concept Created #Working
							- No signs and Symptoms (162848) #Concept Created #Working
SRQ-20 < 6
							- Has signs and symtoms with Low/moderate suicide Risk on Psychotherapy (198872) #Concept Created #Working
SRQ-20 ≥ 6, SAD PERSONs Score ≤7
							- Has signs and symtoms with high suicide Risk on Medication only (198873) #Concept Created #Working
SRQ-20 ≥ 6, SAD PERSONs Score >7
							- Has signs and symtoms with high suicide Risk  on Psychotherapy and Medication (198874) #Concept Created #Working
(SRQ-20 ≥ 6,
SAD PERSONs Score >7)
							- Known mental illness on Psychotherapy only (198875) #Concept Created #Working
							- Known mental illness on Medication only (198876) #Concept Created #Working
							- Known mental illness on Psychotherapy and Medication (198877) #Concept Created #Working
							- Known mental illness NEITHER on Psychotherapy NOR Medication (198878) #Concept Created #Working
							- Recovered (198855) #Concept Created #Working
							- Referred (168758) #Concept Created #Working
							- Not Eligible (1364) #Concept Created #Working
						- MH-A/S (198884) #Concept Created #Working
							- No signs and Symptoms (162848) #Concept Created #Working
Audit - C < 3
							- Has Signs and Symptoms on Brief Intervention (198880) #Concept Created #Working
Audit - C (≥ 3, ≤ 5
							- Has Signs and Symptoms on Brief Intervention/
							  clinical management  (198881) #Concept Created #Working
Audit - C ( > 5
							- Known Alcohol or Substance use disorder  on Brief
							  Intervention and/or clinical management (198882) #Concept Created #Working
(Audit - C (>3)
							- Known Alcohol or Substance use disorder NEITHER
							  on Brief Intervention NOR clinical management (198883) #Concept Created #Working
Audit - C (>3
							- Recovered (198855) #Concept Created #Working
							- Referred (168758) #Concept Created #Working
							- Not Eligible (1364) #Concept Created #Working
				- Nutritional Status (165050) #Concept Created #Working
					- Underweight (123814) #Concept Created #Working
					- Severely underweight
					- Moderate Acute Malnutrition (99271) #Concept Created #Working
					- Severe Acute Malnutrition with no oedema (99272) #Concept Created #Working
					- Severe Acute Malnutrition with oedema  (99273) #Concept Created #Working
					- Normal (1115) #Concept Created #Working
					- Overweight (165301) #Concept Created #Working
					- Obese (165301) #Concept Created #Working
				- Nutrition Support (99054) #Concept Created #Working
					- Therapeutic Feeding (99053) #Concept Created #Working
F75, F100, RUTF
					- Supplementary Feeding (99050) #Concept Created #Working
Flour, oil, sugar, etc
					- Infant and Young Child Feeding Counselling (99051) #Concept Created #Working
<2yrs
					- Nutrition Counselling only (99052) #Concept Created #Working
(if > 2yrs)
					- Not enrolled after nutrition counselling #Concept Not Created
				- Pregnancy Status (90041) #Concept Created #Working
					- Not Pregnant or No BF (90081) #Concept Created #Working
Current concept being used is missleading. Need to create an expliciy concept that reads as the answer
					- Not Applicable. (1175) #Concept Created #Working
					- Breast Feeding (99601) #Concept Created #Working
					- Yes (1065) #Concept Created #Working
					- No (1066) #Concept Created #Working
				- eMTCT Status
					- Yes
					- No
				- Family Planning Set #Concept Not Created
Concept Set not available 
					- Family Planning Status (90238) #Concept Created #Working
						- On family Planning (90082) 
						- Not on Family Planning (90081)
					- Family Planning Method (374) #Concept Created #Working
						- Male #Concept Created #Working
Separated by if statement but no stractual separation
							- Condoms (190) #Concept Created #Working
							- Vasectomy/Tubal ligation (99265) #Concept Created #Working
						- Female #Concept Created #Working
Separated by if statement but no stractual separation
							- Diaphram/Cervical Cap (5278) #Concept Created #Working
							- Oral Contraceptive pills (780) #Concept Created #Working
							- Intra uterine device (IUD) (5275) #Concept Created #Working
							- Injectable (5279) #Concept Created #Working
							- Fertility Awareness Methods (5277) #Concept Created #Working
							- Implants (162961) #Concept Created #Working
							- Vasectomy/Tubal ligation (99265) #Concept Created #Working
							- Condoms (190) #Concept Created #Working
				- Digital Health Messaging Registration #Concept Created
					- Yes (1065) #Concept Created
					- No (1064) #Concept Created
				- CaCx Management
Not a stractual ornaniser but a UI based organization
					- CaCx Screening Visit Type #Concept Created #Working
						- 1st time Screened (198911) #Concept Created #Working
						- Re-screened after previous negative (198912) #Concept Created #Working
						- Post treatment followup (198913) #Concept Created #Working
					- Cervix Cancer Status #Concept Created #Working
						- Negative (664) #Concept Created
						- Postive (703) #Concept Created
						- Cancer Suspect (165314) #Concept Created #Working
						- Invasive Cancer (167764) #Concept Created #Working
						- Not Applicable (1175) #Concept Created #Working
						- Not eligible (1364) #Concept Created #Working
						- Not done (166882) #Concept Created #Working
					- CaCx Sreening Method (198914) #Concept Created #Working
						- HPV (159859) #Concept Created #Working
						- VIA (168711) #Concept Created #Working
						- Pap Smear (885) #Concept Created #Working
					- CaCx treatment  RX (168759) #Concept Created #Working
The trearment offered for CaCx
						- Thermocoagulation (168722) #Concept Created #Working
						- LEEP (168724) #Concept Created #Working
						- Cryotherapy (168723) #Concept Created #Working
				- Syphillis Status (198871) #Working
Currect concepts used depicks results for partner instead of index (99753) needs to change to the current one
					- No Symptoms (162848) #Concept Created #Working
					- No Symptomatic Non-Reactive (198868) #Concept Created #Working
					- No Symptomatic Reactive (198869) #Concept Created #Working
					- Symptomatic Reactive and treated (198870) #Concept Created #Working
				- HIV TB Co-infection
Should be developed as a section but not a stractual or logical selection
					- Completion date (90310) #Concept Created #Working
					- TB Status (90216) #Concept Created #Working
						- Completed TB Treatment (99421) #Concept Created #Working
						- No Signs (90079) #Concept Created #Working
						- Presumptive (90073) #Concept Created #Working
						- Diagnosed
Not a stractual separation but to support explanation of TB Diagnosis status and method. 
							- Chest Xray (165296) #Concept Created #Working
							- TB LAM (165297) #Concept Created #Working
							- TB LAMP #Concept Not Created
Is there a difference between LAM and LAMP
							- TB Microscopy (165298) #Concept Created #Working
							- Gene Xpert/Truenat (165299) #Concept Created #Working
							- Clinically Diagnosed (165295) #Concept Created #Working
							- Other Diagnosed (165300) #Concept Created #Working
						- TB Rx (90071) #Concept Created #Working
Currently on TB treatment
					- TB Regimen (99374) #Concept Created #Working
					- Start date 90217 #Concept Created #Working
					- TB Reg No. (99031) #Concept Created #Working
Could use the TB Identifier
				- Advanced Disease Status(165272)
					- No Advanced HIV Disease (165309)
					- Suspected Advanced Disease (165266)
					- Confirmed Advanced Disease (165267)
CD4<200
				- WHO Clinical Stage (90203)
use T staging for clients ≥ 6months on ART
					- 1 (90033)
					- 2 (90034)
					- 3 (90035)
					- 4. (90036)
					- T1 (90293)
					- T2 (90294)
					- T3 (90295)
					- T4 (90296)
				- Vaccination Status
					- Covid 19 (198849) #Concept Created #Working
						- Covid 19 Vaccination Status (198847) #Concept Created #Working
							- Partial (198844) #Concept Created #Working
							- Completed (1267) #Concept Created #Working
							- Not Vaccinated (198845) #Concept Created #Working
							- Not Eligible (1364) #Concept Created #Working
							- Boosted (198846) #Concept Created #Working
						- Date Completion. (198848)  #Concept Created #Working
					- HPV (198851) #Concept Created #Working
						- Covid 19 Vaccination Status (198850) #Concept Created #Working
							- Partial (198844) #Concept Created #Working
							- Completed (1267) #Concept Created #Working
							- Not Vaccinated (198845) #Concept Created #Working
							- Not Eligible (1364) #Concept Created #Working
							- Boosted (198846) #Concept Created #Working
						- Date Completion. (164992) #Concept Created #Working
				- ADR/Side Effects #Concept Not Created
					- Offending Agent/Intervation (198852) #Concept Created #Working
						- TPT (165225) #Concept Created #Working
						- Dapsone (92) #Concept Created #Working
						- Anti-TB (166370) #Concept Created #Working
						- ARV (1085) #Concept Created #Working
						- Anti-Cancer (198853) #Concept Created #Working
						- Vaccine (1197) #Concept Created #Working
						- CTX (90168) #Concept Created #Working
						- Other (5622) #Concept Not Created #Not In Answer List of Parent
					- Side effects (90227) #Concept Created #Working
					- Grading (198854) #Concept Created #Working
						- None (1107) #Concept Created #Working
						- Moderate (99562) #Concept Created #Working
						- Mild (1498) #Concept Created #Working
						- Severe (1500) #Concept Created #Working
					- Other Offending/Intervation #Concept Not Created
					- Severity (90250) #Concept Created #Working
						- Life Threating (1368) #Concept Created #Working
						- Disability (162558) #Concept Created #Not In Answer List of Parent
						- Hospitalization (167782) #Concept Created #Not In Answer List of Parent
					- Action Taken (198861) #Concept Created #Working
						- Managed Locally (167686) #Concept Created #Working
						- Reffered (168758) #Concept Created #Working
					- ADR Outcome (198859) #Concept Created #Working
						- Recovered (198855) #Concept Created #Working
						- Recovering (198856) #Concept Created #Working
						- Not Recovered (198857) #Concept Created #Working
						- LOST TO FOLLOWUP (5240) #Concept Created #Working
						- Died (160034) #Concept Created #Working
						- Other (5622) #Concept Created #Working
					- Other ADR Outcome (198858) #Concept Created #Working
				- HIV Drug Resistance (168123) #Concept Has error
Concept is not labeled as set yet has set members
					- Date of Sample Collection (198862) #Concept Created #Working
					- Drug (90315) #Concept Created #Working
					- DR Status (198867) #Concept Created #Working
						- Low level resistance (198863) #Concept Created #Working
						- Intermediate Resistance (198864) #Concept Created #Working
						- High level resistance (198865) #Concept Created #Working
						- Susceptible (198866) #Concept Created #Working
				- Pill Balance (165118) #Concept Created
				- Missed Appointment Followup (165346) #Concept Created #Working
					- Followup Date (165373) #Concept Created #Working
					- Followup Method (165100) #Concept Created #Working
					- Reason for Missed Appointment #Concept Created #Working
					- Followup outcome (165104) #Concept Created #Working
			- Counselling
				- Education and Psychosocial
					- Assessement  (PSS1)
A UI Grouping stracture but not a logical or stractal design
						- Issues Identified
A UI Grouping stracture but not a logical or stractal design
							- Psychological /emotional issues (165244) #Concept Has error #Concept Not Created
Separate Social and Psychological issue
								- Denial/coping with result (165260)
								- Anger/ stress (165234)
								- Fear /Anxiety (90118)
								- Bereavement (165233)
							- Social issues (165244) #Concept Has error #Concept Not Created
Separete Social and Psychological issues
								- Non- disclosure (165236)
								- Stigma & discrimination (90150)
								- Dysfunctional family support system (165237)
								- Harmful habits (Alcohol & substance use) (165238)
								- Risky sexual behaviors (165239)
								- Lack of life survival skills (165240)
								- Transition challenges (165241)
								- Economic challenges (165242)
								- Had 1 meal a day #Concept Not Created
								- Malnourished (165219)
						- OVC Screening (165200) #To Display #Concept Created
							- No Signs (165186) #Concept Created
							- Had ≤ 1 meal a day (165223) #Concept Created
							- Not in school  (165273) #Concept Created
							- Malnourished (165219) #Concept Created
							- Care giver unemployed/causal labourer (165220) #Concept Created
							- Non-suppressed viral (164909) #Concept Created
							- Missed Appointment in the last 3 months (165221) #Concept Created
							- Has signs of abuse, exploitation or neglect (165222) #Concept Created
						- OVC Assessment (165212) #Concept Created
							- Not yet Assessed (160737) #Concept Created
							- Assessed, Eligible not yet enrolled (165208) #Concept Created
							- Assessed and Not Eligible (165209) #Concept Created
							- Enrolled (165210) #Concept Created
							- Graduated (165211) #Concept Created
						- GBV/VAC (165302)
							- No signs (165186)
							- Emotional or psychological harm (165187)
							- Physical harm (1490)
							- Inappropriately touched/fondled (165189)
							- Forced sexual intercourse (165262)
						- Patient Categorization (166033) #Concept Created
							- PLHIV newly identified and or re engaging in care when clinically well (198916) #Concept Created
							- PLHIV newly identified and or re-engaging in care with advanced HIV disease (198917) #Concept Created
							- PLHIV established on ART and or with controlled chronic illnesses / NCDs. (198918) #Concept Created
							- PLHIV with uncontrolled chronic illness /NCDs, and any Drug limiting toxicities (198919) #Concept Created
							- PLHIV with treatment failure (198920) #Concept Created
						- Disclosure Set #Concept Not Created
							- HIV Relationship codes #Concept Not Created
								- Spouse (90288)
								- Parent (90279)
								- Children (90280)
								- Not Applicable (1175)
								- Others Specify (5622)
							- Other discloure Relationship #Concept Not Created
							- Disclosed (99175)
								- Yes (90003)
								- No (90004)
					- Advise (PSS2)
						- PHDP components/Advise (165218) #Concept Created
							- STI screening and treatment (165213) #Concept Created
							- FP counseling (99296) #Concept Created
							- FP method provided #Concept Has error #Concept Not Created
Need to create a specific  answer that says Famiy planning provided currently there is Methods of family planning in place of whats expected. 
							- Alcohol and Substance abuse reduction (165214) #Concept Created
							- Risk Reduction Counseling (165215) #Concept Created
							- PMTCT (90012) #Concept Created
							- Disclosure counseling (1167) #Concept Created
							- Management of Stigma & Discrimination (165216) #Concept Created
							- Nutritional Counseling #Concept Has error #Concept Not Created
Import CIEL concept 199088 rather than using (99052) that is to specific to greater than 2 years
							- Basic care package (165217) #Concept Created
							- Others Specify
						- Other PHDP Componet (165265)
Hidden until other is selected from PHDP Componet
					- DSDM (PSS3) 
						- DSDM Model #Concept Not Created
							- GMH - Group models managed by HCW #Concept Not Created
							- GMC - Group models managed by client #Concept Not Created
							- IMC - Individual models based at facilities #Concept Not Created
							- IMF - Individual model based in community #Concept Not Created
						- Approach (PSS3) (165143) #Concept Has error
Rename to DSDM apporach or  Differentiated Service Delivery Approach.
							- GMH
When GMH is selected under model, only models of GMH should appear that is 

GMH-FBG
GMH-CDDP
GMH-FSG
GMH-Varaemia Clinic
GMH-G-ANC/PNC
								- 1 = GMH-FBG (165140) #Concept Created
								- 2 = GMH-CDDP (165142) #Concept Created
								- 3 = GMH-FSG #Concept Not Created
								- 4 = GMH-Viraemia Clinics (198921) #Concept Created
								- 5 = GMH-G-ANC / PNC (198922) #Concept Created
								- 6 = GMH- Others #Concept Not Created
							- GMC
When GMH is selected under model, only models of GMH should appear that is
GMH-CCLAD (165141)
GMH-CLDDP
								- 7 = GMC-CCLAD (165141) #Concept Created
								- 8 = GMC-CLDDP (166496) #Concept Created
								- 9 = GMC- Others
							- IMC
When IMC is selected under model, only models of IMC should appear that is
IMC - CRPDDP (165141)
IMC - Drop in centers
IMC - Home ART Delivery
								- 10 = IMC-CRPDDP (166498) #Concept Created
								- 11 = IMC-Drop in centers #Concept Not Created
								- 12 = IMC-Home ART delivery (198923) #Concept Created
								- 13 = IMC-Others
							- IMF
When IMF is selected under model, only models of IMF should appear that is
IMC - FTDR (165141)
IMC - FBIM (165138)
IMC - adolocent centers (198925)

IMF - Holiday treatment chrildren (198926)
								- 14 = IMF- FTDR (165139) #Concept Created
								- 15 = IMF-FBIM (165138) #Concept Created
								- 16 = IMF-YAPS (198924) #Concept Created
								- 17 = IMF-Adolescent centers (198925) #Concept Created
								- 18 = IMF-Holiday treatment children (198926) #Concept Created
								- 19 = IMF-Others
					- Assist (PSS4)
						- Linkages and Referrals #Concept Created
							- Mental Health Care/Rehabilitation (165264) #Concept Created
							- Livelihood support (165197) #Concept Created
							- GBV /VAC care (165302) #Concept Created
							- Legal Support (165198) #Concept Created
							- Educational Support (165199) #Concept Created
							- OVC services (for all below 20 yrs) (165200) #Concept Created
							- Spiritual care (99558) #Concept Created
							- Community Support (99199) #Concept Created
							- Peer support (165192) #Concept Created
							- Counseling (99560)  #Concept Has error
Concept stated is (99560) which is invividual counseling we need to change it to 167733
							- Nutritional Support (5484) #Concept Created
							- Sexual and Reproductive Health services (165201) #Concept Created
							- Other (5622) #Concept Created
						- ART preparation, readiness, initiation, Adherencesupport& monitoring (165207)
							- Pre-ART Counseling #Concept Not Created
							- ART literacy (165202)
							- Adherence preparation & plan (175321)
							- Ready to start & Initiate (99186)
							- Not ready to start (175320)
							- Ongoing Adherence counseling & support (165206)
							- Intensive Adherence counseling & support (175319)
							- Appointment tracking and followup of lost clients #Concept Not Created
						- Intervention Approaches (165190) #Concept Created
							- Individual counseling (99560) #Concept Created
							- Group Counseling  (99366) #Concept Created
							- Peer counseling (165191) #Concept Created
							- Peer Support Group (165192) #Concept Created
							- Linkages and Referrals (165193) #Concept Created
							- Mobilize for Index testing #Concept Not Created
							- Distribution of HIVST Kits #Concept Not Created
						- Other Linkages And Rifferals (165263)
					- Arrange (PSS5) #Concept Not Created
						- Pharmacy #Concept Not Created
						- Health Facility (165235)
						- School (visit) #Concept Not Created
						- Home (visit) (165103)
						- Community (165331)
						- Virtual Support #Concept Not Created
					- Notes/Comments (160029)
					- Provider
Create provider attribute named cadre and add all these options in there
						- 1 – Medical Officer/Specialist
						- 2 – Clinical Officer
						- 3 – Nurse
						- 4 – Counselor/Social Worker
						- 5 – Peer/Mentor Mother
						- 6 – YAPs
						- 7 - Linkage Facilitator
						- 8 - Para Social Workers
						- 9 - Others Specify........
				- Adherence Counselling
		- Summary
			- Viral Load (165412) #Concept Created #Working
				- Date Bleed (165820) #Concept Created #Working
Consider changing it to the encounter date for the encounter 
				- VL Qualitative (1305) #Concept Created #Working
				- VL Quantitative (856) #Concept Created #Working
				- VL Suppression #Calculated Field
Consider calculating it based on range
			- TPT
				- TPT Start Date (165226) #Concept Created
				- TPT Completion Date (165227) #Concept Created
				- TPT Drug #Concept Not Created
				- TPT Status (165288) #Concept Created
			- Transfer Details
				- Transfer Out (99166) #Concept Created #Working
					- Transfer Out Date (99165) #Concept Created #Working
					- Transferred Out to (90211) #Concept Created #Working
				- Transfer In
					- Transfer in Date 
					- Transfered from
			- Current Regimen
				- Regimen Line
				- Date Started
				- Regimen
			- Baseline Information (99162)
				- ART Start Date (99161)
				- Date Positive HIV Test Comfirmed (168120)
				- Baseline Regimen (99061) 
				- Baseline CD4 (99071)
				- Baseline Weight (99069)
				- Baseline WHO Clinic Stage (99070)
			- Last Visit Summary
				- Current Regimen (90315)
				- Who Clinic Stage (90203)
				- Regimen Line (164515)
	- EID Care
	- TB Program
- Conditions #Working
- Allergies #Working
- Diagnosis
Need to return the diagnosis form of OpenMRS default
- Orders
	- Lab Order
		- Lab Order Form
			- From ACP 003
				- Viral Load (165412) #Concept Created #Working
					- HIV VIRAL LOAD QUANTITATIVE (856) #Concept Created #Working
					- VIRAL LOAD QUALITATIVE (1305) #Concept Created #Working
				- LFTs (166522)
					- ALT/SGOT (166429)
					- AST/SGOT (166423)
					- Bilirubin in urine (166203)
					- PT (166330)
					- PT (166330)
					- Albumin (166519)
					- LD (166520)
					- GGT (166521)
					- TOTAL PROTEIN (717)
				- RFTs
					- Creatinine (166523)
					- Urea (166524)
					- GFR (166525)
					- Na+ (166526)
					- Cl (166528)
					- K+ (166527)
				- TB LAM
				- TB LAMP
				- GeneXpert
				- Microscopy
				- CD4 (657)
					- CD4 COUNT (5497)
					- CD4% (730)
				- HIV Drug Resistance
				- CrAg
				- RPR
				- HEP B
				- HEP C
				- RBS
				- FBS
				- CBC
			- From TB 003 
		-  
	- Medication Orders
	- Procedure Orders

### Laboratory

#### Accession Sample
- Assign Lab Number
- Refer Sample
When Refereing a sample, a Bar code can be assigned and comfired, a refereal lab selected and sample sent to refereal lab. 
- Send Sample for testing
When a sample is sent to for testing, Its can be found in worklist. 

#### Reject Sample
	A sample rejected is added to a rejected list.

#### Result Sample
	This process involves adding results to a sample. Some tests do have a single test result while others do have multiple variables/parameters. 

#### Approve Results
	Results added to samples have to be approved by a lab personel to ensure that they return to clinicians. 
	On approval, results are returned to the clinician. 

### Pharmacy

### Stores/Stock mgt