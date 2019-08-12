# DRAFT

## SUMMARY
AbleVets team had uploaded all required documents including the POAMs for final ATO submission before the freeze of RV on July 14, 2019.

Our team had to wait for 3 week for eMASS training and RV to eMASS transition from July 14, 2019 to July 29, 2019, then Aug 3rd Security Lead regaining access to EMASS. Configuration of VAM to EMASS Aug 9th. 

During the eMASS training, we learned of the new ATO package approval process in eMASS. We determined that unlike RiskVision, eMASS requires at least twice as many steps (See Image) in the approval process, which in-effect, incurs more dependency on VA availability. In other words, there is a greater chance of delay due to being dependent upon others and their schedules (PTO, training, common work and etc) in getting approvals to receive an ATO in eMASS compared to RiskVision. Additionally,  we learned that the entire VA network staff related to eMASS is also learning this new system, thus creating further delay. Moreover,  given the number of systems transitioning from RiskVision to eMASS, the current staff required in the approval process of an ATO is limited. 

During the training we determined that the estimated time it takes for an ATO process in eMASS, from start to finish, is about 9 months at the least.  Now, this is based on a system just starting out, but for us and factoring everything we stated above, we estimated that our process till ATO approval is at least 3-4 months, if not more. 

So, this prompted us to dig further into figuring out a way to avoid this new delay, which resulted in us understanding the process of a conditional 1-year ATO. And decided to get the SO, ISO, VA PM, and BO to accept the 1-year ATO instead, which was initially considered a conditional ATO of 30 or 120 days, but it is now a single year conditional ATO. 
The 1-year ATO are typically for projects which need to address specific concerns at a faster rate (Escalated) for whatever reason, and our reason is sufficient, since the eMASS migration could and likely hinder our ability to complete an ATO in time before IOC and/or possibly the contract end date. 

The 1-year conditional ATO will essentially shotgun through the normal approval process and save us roughly 3-4 months at the minimum. However, the VA can still disapprove our ATO, but given the work done in RV and the amount of counseling that we have had from our ISO, we see no reason why that will happen, because we will have everything needed for a conditional approval from the Authorizing Official (AO) in eMASS. Even with a denial, we will still be able to resubmit for the 1-year conditional ATO and make better time than the normal ATO process.

</br> </br> </br> </br>
## Gap between RiskVision and eMASS Autohiration: 

### RiskVision:
1.	Completion rate: 4-6months 
2.	45day ATO approval review process 
3.	Number of controls: 390 (+ or - )

### EMASS: 
1.	Completion rate: 6-9 months
2.	60day ATO approval review process 
3.	Number of controls: Additional 360 controls 

.
.
.
.</br> </br> </br> </br>
.
## Timeline of accomplishments in RV:
1.	SO signs ATO documents May 9th, but only to have them be reversed by ISSO decision. 
2.	May 22nd, Security Lead confirms officially with Lead Cloud Architect, 2 ISSOs, PM and COMMS representatives to reclassify VAM as a PaaS. Complete redo of VAM as an IaaS to a PaaS follows. 
3.	Around late June 24th time frame, 2019 AbleVets had all (Minus IRP and Re-edited PIA. Note: PIA was signed initially) the documents completed and uploaded in RV with all required signatures.
4.	Around early July, the IRP was finally finalized and signed, then uploaded. To also include, the revised and resigned PIA
5.	There was an issue with the Secure/Quality Scans with the way the RPC calls are being made and the VA being unable to identify our credentials. Also, various Fortify updates changed during the resubmission, which created further delay, thus resulting re-updating Fortify to remediate the finding.  AbleVets team worked with the ISO, BO and the technical team to document proper response to the accepted risks of the RPC traffic in question through a POAM in RV. 4 week delay. 
6.	AbleVets decided to create and upload a POAM for the Nessus Scan as it was taking long for VA to run the scans prior to being unable to identify VAM devices and credentials. 1 week delay in trouble shooting and then a mandated scan completion date of July 15th. AbleVets had to create new servers to remedy VA’s inability produce correct configuration to asses VAM system. 
7.	After the July 15th Nessus scan completion date, the scan came back with numerous findings which mostly comprised of updates, and false/positives. 
8.	AbleVets created multiple evidence justification documents to claim N/A on various scans, such as WASA, Secure Design/ThreatModel, ISA/MOU. EDS scan has been on constant delay due to inability and delay of PM being able to gain access to submit scan. Scan is likely an N/A, but receipt is desired to prove result. 
9.	Around July 02nd, AbleVets request RiskVision review for ATO submission to follow. 
10.	AbleVets learns, 4 days prior, through ISSO, that the ASOB stopped reviewing ATOs across VA on July 11, 2019 
11.	During the same meeting, ISSO advises that RiskVision will be turned into a Read-Only mode tool from July 14, 2019
12.	ISSO stated she will not approved ATO if submitted prior to ASOB ending its reviews. 
13.	AbleVets Security Engineer completed his eMASS training on July 31, 2019 
14.	VA completed the RiskVision to EMASS migration on July 29, 2019 
15.	AbleVets’ Security Engineer’s System Steward access re-activated for eMASS on August 02, 2019 (Still Waiting on one more AbleVets Security Engineer to regain System Steward access)
16.	AbleVets to recategorize and implement VAM into eMASS, per ISSO guidance (on Aug1st) on Aug 9th 
.
.
.
.</br> </br> </br> </br>
.
## eMASS Controls updated by AbleVets
![eMASS Controls](https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/eMASS_Transition/images/Controls_eMASS.PNG "eMASS Controls updated by AbleVets")
.
.
.
.</br> </br> </br> </br> 
.
## eMASS Autorization Workdlflows
![eMASS Workflows](https://github.com/vistadataproject/VAM2ProjectManagement/blob/master/eMASS_Transition/images/eMASS_Workflows.jpg "eMASS Authorization Workflows") |