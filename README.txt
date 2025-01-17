# Gun-Ownership-effects-on-Homicide
Gun Ownership effects on Homicide


The dataset is compiled from the U.S. Census Bureau USA Counties Database and can be downloaded at http://www.census.gov/support/USACdataDownloads.html. Variables include county- level measures of demographics, the age distribution, the income distribution, crime rates, federal spending, home ownership rates, house prices, educational attainment, voting paterns, employment statistics, and migration rates.

OBJECTIVE:
Estimates the effect of gun ownership on the homicide rate using double machine learning methods. Several methods are used to partial out the outcome and treatment variable from the control variables. The estimates are calculated by regressingpartialled out outcome variable on partialled out treatment variable.




Rows: 3900
variables: 415



Census Variables :

AGE010D - Pop 1980, 1990
AGE050D - Median Age 1980, 1990
AGE110D - Pop < 5 1980, 1990
AGE170D - Pop 5 to 14 1980, 1990
AGE180D - Pop 5 to 17 1980, 1990
AGE270D - Pop < 18 1980, 1990
AGE310D - Pop 18+ 1980, 1990
AGE320D - Pop 20 to 24 1980, 1990
AGE350D - Pop 25 to 29 1980, 1990
AGE380D - Pop 25 to 34 1980, 1990
AGE410D - Pop 30 to 34 1980, 1990
AGE470D - Pop 35 to 44 1980, 1990
AGE570D - Pop 45 to 54 1980, 1990
AGE640D - Pop 55 to 59 1980, 1990
AGE670D - Pop 60 to 64 1980, 1990
AGE760D - Pop 65+ 1980, 1990
BNK010D - # Commercial Banks, 1980, 1985+
BNK050D - Total Bank Deposits, 1980, 1985+
BPS020D - New housing by building permits 1984-1993 (17000 universe)
BPS030D - New housing by building permits 1994-2010 (19000 universe)
BPS120D - Valuation of new housing by building permits 1984-1993 (17000 universe)
BPS130D - Valuation of new housing by building permits 1994-2010 (19000 universe)
BPS220D - New housing by building permits, Single-family 1984-1993 (17000 universe)
BPS230D - New housing by building permits, Single-family 1994-2010 (19000 universe)
BPS820D - New housing by building permits, 5+ family 1984-1993 (17000 universe)
BZA010D - Private nonfarm establishments, 1980-2008
BZA110D - Private nonfarm employment, 1980-2008
BZA210D - Private nonfarm annual payroll, 1980-2008
EDU100D - School enrollment 3 years and over, 1980
EDU200D - School enrollment 3 years and over, 1990
EDU600D - Persons 25 years and older 1980, 1990
EDU610D - Persons 25 years and older with < 9th grade, 1980, 1990
ELE010D - Vote cast for president, total: 1980:4:2000
ELE020D - Vote cast for president, democrat: 1980:4:2000
ELE025D - % voting democrat: 1980:4:2000
ELE030D - Vote cast for president, republican: 1980:4:2000
ELE035D - % voting republican: 1980:4:2000
ELE060D - Vote cast for president, other: 1980:4:2000
ELE065D - % voting other: 1980:4:2000
ELE210D - % voting for leading party: 1980:4:2000
ELE220D - Leading party code: 1980:4:2000
HIS010D - Total persons, 1980, 1990
HIS020D - Hispanic persons, 1980, 1990
HIS030D - Hispanic females, 1980, 1990
HIS040D - Hispanic males, 1980, 1990
HIS110D - Hispanic persons 5-14 yrs, 1980, 1990
HIS120D - Hispanic persons 15-59 yrs, 1980, 1990
HIS130D - Hispanic persons 60-64 yrs, 1980, 1990
HIS140D - Hispanic persons 65+ yrs, 1980, 1990
HIS200D - Hispanic persons 25+ yrs, 1980
HIS300D - Hispanic persons 25+ yrs, 1990
HIS500D - Hispanic families, 1980
HIS700D - Hispanic households, 1990
HSD010D - Households, 1980, 1990
HSD020D - Households, % Change
HSD030D - Households with persons 65+, 1980, 1990
HSD110D - Family households, 1980, 1990
HSD120D - Family household with people < 18, 1980, 1990
HSD130D - Family households, married, 1980, 1990
HSD140D - Family households, married with people < 18, 1980, 1990
HSD150D - Family households, male head, no spouse, 1980, 1990
HSD170D - Family households, female head, no spouse, 1980, 1990
HSD200D - Nonfamily households, 1980, 1990
HSD210D - Nonfamily households, one person, 1980, 1990
HSD230D - Nonfamily households, one person, female head, 1980, 1990
HSD300D - Persons in household, 1980, 1990
HSD310D - Persons per household, 1980, 1990
HSD410D - Households, total, 1980, 1990
HSD500D - Family households, 1980, 1990
HSD510D - Family households, married couple, 1980, 1990
HSD520D - Family households, married couple with own children, 1980, 1990
HSD530D - Family households, married couple without own children, 1980, 1990
HSD540D - Family households, male head, no spouse, 1980, 1990
HSD550D - Family households, male head, no spouse, own children under 18, 1980, 1990
HSD560D - Family households, male head, no spouse, without own children under 18, 1980, 1990
HSD570D - Family households, female head, no spouse, 1980, 1990
HSD580D - Family households, female head, no spouse, own children under 18, 1980, 1990
HSD590D - Family households, female head, no spouse, without own children under 18, 1980, 1990
HSD610D - Nonfamily households, 1980, 1990
HSD620D - Nonfamily households, one person, 1980, 1990
HSD710D - Persons in households, 1980, 1990
HSD720D - Persons in family households, householder 1980, 1990
HSD730D - Persons in family households, spouse 1980, 1990
HSD740D - Persons in family households, other relative 1980, 1990
HSD750D - Persons in family households, nonrelatives 1980, 1990
HSD760D - Persons in nonfamily households, male head 1980, 1990
HSD770D - Persons in nonfamily households, female head 1980, 1990
HSD780D - Persons in nonfamily households, nonrelatives 1980, 1990
HSG030D - Total housing units, 1980, 1990
HSG040D - Total housing units (revised), 1980, 1990
HSG045D - Total housing units, %change
HSG050D - Total housing units, sample 1980, 1990
HSG182D - Housing tenure, occupied housing units, owner-occupied, 1980, 1990
HSG195D - Vacant housing units, 1980, 1990
HSG200D - Occupied housing units, 1980, 1990
HSG210D - Occupied housing units, black householder, 1980, 1990
HSG220D - Occupied housing units, Hispanic householder, 1980, 1990
HSG230D - Occupied housing units (sample), 1980, 1990
HSG240D - Occupied housing units with < 1 person per room, 1980, 1990
HSG250D - Occupied housing units with > 1 person per room, 1980, 1990
HSG310D - Occupied housing units, utility gas, 1980, 1990
HSG315D - Occupied housing units, Bottled, tank, LP gas, 1980, 1990
HSG320D - Occupied housing units, Electricity, 1980, 1990
HSG325D - Occupied housing units, Fuel oil, 1980, 1990
HSG335D - Occupied housing units, wood, 1980, 1990
HSG350D - Occupied housing units, no fuel, 1980, 1990
HSG370D - Occupied housing units, no vehicle available, 1980, 1990
HSG375D - Occupied housing units, 1 vehicle, 1980, 1990
HSG380D - Occupied housing units, 2+ vehicle, 1980, 1990
HSG440D - Owner-occupied housing units, 1980, 1990
HSG445D - Owner-occupied housing, percent of total, 1980, 1990
HSG450D - Owner-occupied housing with black householder, 1980, 1990
HSG460D - Owner-occupied housing with Hispanic householder, 1980, 1990
HSG490D - Median value of owner-occupied housing, 1980, 1990
HSG500D - Owner-occupied housing value < $20000, 1980, 1990
HSG510D - Owner-occupied housing value $20000 - 29999, 1980, 1990
HSG520D - Owner-occupied housing value $30000 - 39999, 1980, 1990
HSG530D - Owner-occupied housing value $40000 - 49999, 1980, 1990
HSG540D - Owner-occupied housing value $50000 - 99999, 1980, 1990
HSG550D - Owner-occupied housing value $100000 - 149999, 1980, 1990
HSG560D - Owner-occupied housing value $150000 - 199999, 1980, 1990
HSG570D - Owner-occupied housing value $200000+, 1980, 1990
HSG650D - Median monthly owner costs, 1980, 1990
HSG680D - Renter occupied housing, 1980, 1990
HSG690D - Renter occupied housing, black householder, 1980, 1990
HSG700D - Renter occupied housing, Hispanic householder, 1980, 1990
HSG710D - Renter occupied housing (sample), 1980, 1990
HSG730D - Median rent, 1980, 1990
INC110D - Median Household Income 1979, 1989, 1999
INC650D - Families with income < 10000 1979, 1989, 1999
INC670D - Families with income 10000-14999 1979, 1989, 1999
INC680D - Families with income 15000-19999 1979, 1989, 1999
INC690D - Families with income 20000-24999 1979, 1989, 1999
INC700D - Families with income 25000-29999 1979, 1989, 1999
INC710D - Families with income 30000-34999 1979, 1989, 1999
INC720D - Families with income 35000-39999 1979, 1989, 1999
INC730D - Families with income 40000-49999 1979, 1989, 1999
INC760D - Families with income 50000-74999 1979, 1989, 1999
INC790D - Families with income >74999 1979, 1989, 1999
LFE020D - Employment Status - in labor force, total 1980, 1990, 2000, 2005-2009
LFE023D - Employment Status - in labor force, males 1980, 1990, 2000, 2005-2009
LFE030D - Employment Status - in labor force, armed forces 1980, 1990, 2000, 2005-2009
LFE080D - Families with no workers 1980, 1990, 2000
LFE090D - Families with 2 or more workers 1980, 1990, 2000
LFE210D - Means of Transportation to work car, truck, or van - drove alone 1980, 1990, 2000, 2005-2009
LFE220D - Means of Transportation to work car, truck, or van - carpooled 1980, 1990, 2000, 2005-2009
LND110D - Land Area in Square Miles 1980, 1990, 2000, 2010
PIN020D - Per Capita Personal Income - yearly 1969-2000
POP110D - Urban population 1980:10:2000
POP210D - White Population 1960:10:1990
POP240D - Black Population 1960:10:1990
POP440D - Males 15 yrs and over never married 1980:10:2000, 2005-2009
POP450D - Males 15 yrs Married but separated 1980:10:2000, 2005-2009
POP470D - Males 15 yrs Widowed 1980:10:2000, 2005-2009
POP480D - Males 15 yrs Divorced 1980:10:2000, 2005-2009
POP540D - Females 15 yrs and over never married 1980:10:2000, 2005-2009
POP550D - Females 15 yrs Married but separated 1980:10:2000, 2005-2009
POP570D - Females 15 yrs Widowed 1980:10:2000, 2005-2009
POP580D - Females 15 yrs Divorced 1980:10:2000, 2005-2009
POP700D - Persons 5 yrs and over by residence - Total 1980:10:2000
POP710D - Persons 5 yrs and over by residence - Same house for in last 5 yrs 1980:10:2000
POP720D - Persons 5 yrs and over by residence - Different house same county in last 5 yrs 1980:10:2000
POP730D - Persons 5 yrs and over by residence - Diifferent County same state in 5 last yrs 1980:10:2000
POP740D - Persons 5 yrs and over by residence - Different State or abroad in last 5 yrs 1980:10:2000
PPQ010D - Persons in Group Quarters 1980:10:2010
PPQ100D - Institutionalized population 1980:10:2010
PPQ110D - Institutionalized population - Correctional facility 1990:10:2010
PPQ120D - Institutionalized population - Nursing home 1990:10:2010
PVY020D - Persons below poverty level 1969,1979,1989,2005-2009
PVY120D - Persons over 18 below poverty level 1989,2005-2009
PVY210D - Persons 65 yrs and over below poverty level 1979,1989,2005-2009
PVY310D - Related Children beloiw 18 yrs below poverty 1979,1989,2005-2009
PVY420D - Families below poverty level 1969,1979,1989,2005-2009
PVY520D - Families with female househead, no spouse below poverty level 1979,1989,2005-2009
SPR030D - Social Security Benefit Payements 1990:1:2010
SPR130D - Social Security Retired Workers Benefit Payements 1990:1:2010
SPR230D - Social Security Widows and Widowers Benefit Payements 1990:1:2010
SPR330D - Social Security Disabled Workers Benefit Payements 1990:1:2010
SPR440D - Social Security Ave Monthly Payments per recipient 1990:1:2010
VST020D - Births per 1000 populatioin 1970:5:1990, 1991:1:2007


Other Variables: 

logghomr        : Log gun homicide rate
burg_missing    : Indicator for missing burglary data
robrate_missing : Indicator for missing robbery data
CountyCode 	 : Country Code 
logburg		 : Burglary Rate
logfssl		 :        
logrobr		 : Log robbery


Fixed Effect Dummies: 

X_Tyear1-21  : Year Fixed Effect
X_Jfips1-195 : County Fixed Effect


Constructed Variables: These variables are constructed from the Census variables.

newblack: 

blackpct = 100* POP240D / AGE010D ;
black80 = mean(blackpct*(year == 80))  ;
black90 = mean(blackpct*(year == 90))
log(black80*(year < 90)+black90*(year > 89)) ;


newdens:

100* POP110D / AGE010D
dens80 = mean(density*(year == 80))  ;
dens90 = mean(density*(year == 90))  ;
log(dens80*(year < 90)+dens90*(year > 89))

newfhh:

fhhldpct = 100* HSD570D / HSD010D ;
fhh80 = mean(fhhldpct*(year == 80))  ;
fhh90 = mean(fhhldpct*(year == 90))  ;
log(fhh80*(year < 90)+fhh90*(year > 89))


newmal:

mal80 = mean(malunpct*(year == 80))  ;
mal90 = mean(malunpct*(year == 90))  ;
log(mal80*(year < 90)+mal90*(year > 89))


newmove:

moverpct = 100*( 1 - POP710D / POP700D)
move80 = mean(moverpct*(year == 80))  ;
move90 = mean(moverpct*(year == 90))  ;
newmove = log((100-move80)*(year < 90)+(100-move90)*(year > 89))



