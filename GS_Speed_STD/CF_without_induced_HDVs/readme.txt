original results file:
	0_1000.csv ~ 0_10000.csv
	1_1000.csv ~ 1_10000.csv
	GS_CF_without_aggregate.csv

mission:
	add speed std for each GS data segement

code: 
	Calculate_Speed_STD.jpynb

result:
	the record after we add speed std:
		new_GS_record_issdc_1.csv
		new_GS_record_issdc_0.csv
		new_GS_record_total.csv

	the speed std distribution for each record:
		issdc_1_SpeedSTD_Distribution.csv
		issdc_0_SpeedSTD_Distribution.csv
		issdc_total_SpeedSTD_Distribution.csv

	the histogram of the speed std distribution for each record:
		GS_Speed_STD_issdc_1.jpg
		GS_Speed_STD_issdc_0.jpg
		GS_Speed_STD_total.jpg