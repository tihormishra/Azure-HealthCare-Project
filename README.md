# Azure-HealthCare-Project
HealthCare Project
Technology - Azure Data Engineering Stack

Healthcare Revenue Cycle Management (RCM)

RCM is the process that hospitals use to manage the financial aspects, from the time the patient schedules an appointment till the time the provider gets paid..

Here is a simplified breakdown:

1. It starts with a patient visit:
 patient details are collected, Insurance details are collected
 This ensures provider knows who will pay for the services
 insurance, the patient, or both 

 20000 USD

 15000 USD - Insurance
 5000 USD - Patient


2. Services are provided


3. Billing happens: The hospital will create a bill.


4. Claims are reviewed: Insurance company review the bill

they might accept it, pay in full, or partial or decline.


5. Payments and followups

if partial payment is done by insurance company,

then some portion or complete thing is given by the patient...

and the providers will followup for the payment


6. Tracking and improvement: 

RCM ensures the hospital can provide quality care while also staying financially healthy.


As part of RCM we have 2 main aspects

- Accounts Receivable (AR)
- Accounts Payable


Patient paying is often a risk

scenarios when patient has to pay

Low Insurance - these insurance providers put most of the burden on patients..

Private Clinics
Dental treatments
Deductibles

2 objectives for AR
- Bring cash
- also minimize the collection period

the probability of collecting your full amount decreases with time..

- 93% of money due 30 days old...
- 85% of money due 60 days old...
- 73% of money due 90 days old...

KPI to measure AR and set benchmarks...

1. AR > 90 days...

200K USD older then 90 days

1 million USD

200k / 1 million = 20%


2. Days in AR

1 million USD in 100 days

per day 10000 USD

400K USD AR

40 DAY

45 Days..

we will have data in various Sources

we need to create a pipeline, the result of this pipeline will be fact tables and dimension tables, will help the reporting team to generate the KPI
