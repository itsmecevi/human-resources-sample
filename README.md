# human-resources-sample

This is a Doku for human-resources sample with Power BI.

Source: 
https://docs.microsoft.com/en-us/power-bi/sample-human-resourcesfrom http://obvience.com/

The dataset: [Click here](https://drive.google.com/file/d/1v1yIKaWxUesQRnx7Mzr7LSq-52kjANd6/view?usp=sharing)

Before going further, we need understand the concept of the data model, please read the link below:
https://en.wikipedia.org/wiki/Data_model

This analysis contains 9 entity (table) and every table has attribute to.

1. age group
* Attribute: AgeGroupID,	AgeGroup

2. gender
* Attribute: ID, Gender,	Sort

3. ethnicity
* Attribute: Ethnic Group,	Ethnicity

4. date
* Attribute: Date,	Month,	MonthNumber,	Period,	PeriodNumber,	Qtr,	QtrNumber,	Year,	Day,	MonthStartDate,	MonthEndDate,       MonthIncrementNumber

5. separation reason 
* Attribute: SeparationTypeID,	SeparationReason

6. pay type
* Attribute: PayTypeID,	PayType

7. FP
* Attribute: FP,	FPDesc

8. bu
* Attribute: BU,	RegionSeq,	VP,	Region

9. employee_fact
* Attribute: date,	EmplID,	Gender,	Age,	EthnicGroup,	FP,	TermDate,	isNewHire,	BU,	HireDate,	PayTypeID,	TermReason,	AgeGroupID	,TenureDays,	TenureMonths,	BadHires



### Let's make the data model from the 9 entity. Just drag every [Primary Key](https://en.wikipedia.org/wiki/Primary_key) of the entity in power pivot or power bi data model

![human-resources-data-model](https://user-images.githubusercontent.com/27078712/40884676-aae46c40-6718-11e8-9686-0b07b9f79367.PNG)





### After that, create [a measure in power bi or power pivot](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-create-measures)

Below are the measure of every graph,

Note! we use the format of table and attribute with [DAX language](https://docs.microsoft.com/en-us/power-bi/desktop-quickstart-learn-dax-basics) 

Extras: [Quick Guide DAX](https://support.office.com/en-us/article/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a?omkt=en-US&ui=en-US&rs=en-US&ad=US)

---------------------------------------------------------------------------
Drag this entity for every graph: 
.
.
.coming soon!
