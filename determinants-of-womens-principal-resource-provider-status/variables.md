# Variables
## All
### Housing, Household, and Individual Identification
- REGION: 'Region of residence'
- NUMENQ_ANON: 'Anonymized investigator number'
- NUMFA: 'Address sheet number'
- SSECH: 'Sample code'
- V: 'Wave'
- LE: 'Not specified'
- EC: 'Not specified'
- IDENT_FA: 'Address sheet identifier'
- IDENT_LOG: 'Housing identifier'
- IDENT_MEN: 'Household identifier'
- DOUBLONTYPE: 'Duplicate type'
- NUMFA_SOURCE: 'Source address sheet number'
- SSECH_SOURCE: 'Source sample code'
- IDENT_FA_SOURCE: 'Source address sheet identifier'
- IDENT_LOG_SOURCE: 'Source housing identifier'
- IDENT_MEN_SOURCE: 'Source household identifier'
- IDENT_IND_SOURCE: 'Source individual identifier'
- IDENT_IND: 'Individual identifier'
- TYPREPQAA: 'QAA response indicator'
- CHAMP_CT2005: '2005 working conditions survey field'

### Civil Status
- SEXE: 'Sex'
- MNAIS: 'Month of birth'
- ANAIS: 'Year of birth'
- AGE: 'Age at the time of the survey'
- AGEQ: 'Quinquennial age at the time of the survey'
- LNAIS: 'Place of birth indicator'
- DEPNAIS: 'Birth department/territory'
- NAIS7: 'Grouped birth place code'
- LNAISD: 'Place of birth code'
- ANARRIV: 'Year of arrival in France'
- AGARRIV: 'Age at arrival in France'

### Family Situation
- COUPLE: 'Living as a couple'
- COUPLRP: 'Living as a couple according to RP'
- CONJOINT: 'Spouse order number in the household'
- ETAMATRI: 'Legal marital status'
- PACS: 'Existence of a PACS'
- MER1E: 'Presence of mother in the household'
- PER1E: 'Presence of father in the household'

### Housing Situation
- TYPOLOG: 'Housing occupation type'
- AUTLOG: 'Existence of other housing'

### Main Situation Regarding Work and Reference Group
- IPROPLOC: 'Primary occupant indicator'
- SITUA: 'Main situation regarding work'
- TRAREF: 'Paid work last week'
- PASTRA: 'Having a job despite interruptions'
- RABS: 'Has a job but did not work'
- RABSP: 'Interruption period'
- RABSPU: 'Time unit of the interruption'
- DUREE_CESSATION: 'Duration in days of the interruption'
- AIDFAM: 'Family or cohabiting partner assistance'
- INFORM: 'Informal activities'
- STATUTEXT: 'Status (extended FP)'
- PRACT: 'Current primary resource provider indicator'
- IPRAN: 'Primary household resource provider indicator for the year'

### Detailed Professional Life
- PRINACT: 'Main activity'
- ACT2: 'Second activity'
- HORAIRE: 'Working hours'
- JOURS: 'Number of days worked'
- EMPSIT: 'Employment situation'
- NBFCTRA: 'Number of work contracts'
- CNFCTRA: 'Current work contract'
- SECTEUR: 'Activity sector'

### Working Conditions and Health
- METIER: 'Job'
- SANTE: 'Health status'
- ACCID: 'Work accidents'
- MALPRO: 'Occupational diseases'
- FATIGUE: 'Work-related fatigue'

### Income and Living Conditions
- REVENUS: 'Household income'
- DEPENSES: 'Monthly expenses'
- AIDE: 'Social aid'
- SATIS: 'Satisfaction with living conditions'
- ENDETTEMENT: 'Debt level'

### Relationship with Household Reference Person
- LIENPREF: 'Link to the household reference person'

### Calculated Household Variables
- TCM_M: 'Calculated variable for the household'
- CALCULEE: 'Calculated variable'

### Indicator of Belonging to the Main Family
- FAMPRINC: 'Main family membership indicator'
- ENFANT: 'Child of the household'
- CJSITUA: 'Spouse’s main work situation'

### Relationship of the Surveyed Person with Household Members
- LIEN_01 to LIEN_20: 'Link of the surveyed person with the household member having individual order number 1 to 20'

### Household Type
- TYPMEN5: 'Household type according to TCM'
- TYPMEN15: 'Detailed household type according to TCM'

### Spouse Indicator
- CJACTOCCUP: 'Active spouse according to the survey'
- CJENQUETE: 'Spouse is a “kish” (was selected to answer the survey)'

### Number of Children in the Household
- NBENFM3: 'Number of children (or stepchildren) under 3 years old in the household'
- NBENF3A17: 'Number of children (or stepchildren) aged 3 to 17 in the household'
- NBENF18P: 'Number of children (or stepchildren) 18 years and older in the household'

### Number of People and Active Members in the Household
- NPERS: 'Number of people in the household'
- NACTIFS: 'Number of active members in the household'
- Selected Individuals for QAO:
- NOIK1: 'Individual order number of the first person selected for QAO'
- NOIK2: 'Individual order number of the second person selected for QAO (if applicable)'

### Income
- TOTREVEN: 'Average declared monthly income'
- TOTREVEN_DRAP: 'Flag variable for TOTREVEN'
- ITOTREV: 'Income completeness indicator'
- TRANCHRE: 'Average declared monthly income in range'
- REVMEN: 'Average declared monthly income'
- REVMENMN: 'Average monthly income, lower bound (of the range)'
- REVMENMX: 'Average monthly income, upper bound (of the range)'
- COEFFUC: 'Sum of consumption units'
- REVMENUC: 'Average monthly income per consumption unit'
- REVMENMNUC: 'Average monthly income, lower bound per consumption unit'
- REVMENMXUC: 'Average monthly income, upper bound per consumption unit'

------------------------------------------------------------------------------------------

## 2nd tri 

### Variables related to Civil Status and Family:
ANAIS: Year of birth
ETAMATRI: Legal marital status
PACS: Existence of a PACS
MER1E: Presence of mother in the household
PER1E: Presence of father in the household

### Variables related to Work Situation:
SITUA: Main situation regarding work
CJSITUA: Spouse’s work situation
RABS: Reason for not working
STATUTEXT: Status (extended FP)
SSECH: Activity sector
METIER: Job (potentially linked to professional activity)

### Variables related to Income and Living Conditions:
REVMENUC: Average monthly income per consumption unit
AIDFAM: Family or cohabiting partner assistance

### Variables related to Housing and Family Characteristics:
TYPOLOG: Housing occupation type
TYPMEN15: Household type according to TCM
NPERS: Number of people in the household
NACTIFS: Number of active members in the household
NBENFM3, NBENF3A17, NBENF18P: Number of children in the household

* Potentially collinear variables:
* ANAIS and AGE (if included) may be strongly correlated.
* MER1E and PER1E may be correlated if both parents are present together.
* REVENUS and DEPENSES may be correlated.
* NBENFM3, NBENF3A17, NBENF18P may be correlated with each other.
* REVENUS and COEFFUC may be correlated.

------------------------------------------------------------------------------------------

## 3rd tri 

### Civil Status and Family:
ANAIS: Year of birth
ETAMATRI: Legal marital status
PACS: Existence of a PACS
MER1E: Presence of mother in the household
PER1E: Presence of father in the household

### Work Situation:
SITUA: Main situation regarding work
CJSITUA: Spouse’s work situation
RABS: Reason for not working
STATUTEXT: Status (extended FP)
METIER: Job (potentially linked to professional activity)

SSECH: Activity sector ----> Excluded due to multicollinearity with STATUTEXT

### Living Conditions:
REVMENUC: Average monthly income per consumption unit
AIDFAM: Family or cohabiting partner assistance

### Variables related to Housing and Family Characteristics:
TYPOLOG: Housing occupation type
TYPMEN15: Household type according to TCM
NPERS: Number of people in the household
NACTIFS: Number of active members in the household

NBENFM3, NBENF3A17, NBENF18P: Number of children in the household ----> Excluded due to multicollinearity with NPERS

#################

numerical values: ['ANAIS', 'REVMENUC', 'NPERS', 'NACTIFS']

categorical_values: ['ETAMATRI', 'PACS', 'MER1E', 'PER1E', 'SITUA', 'CJSITUA', 'RABS', 'STATUTEXT', 'METIER', 'AIDFAM', 'TYPOLOG', 'TYPMEN15']
