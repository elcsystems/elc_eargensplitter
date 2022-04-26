EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Connector:AudioJack2 J1
U 1 1 627E7B24
P 2300 5600
F 0 "J1" H 2332 5925 50  0000 C CNN
F 1 "AudioJack2" H 2332 5834 50  0000 C CNN
F 2 "Custom:Jack_6.35mm_Mono" H 2300 5600 50  0001 C CNN
F 3 "~" H 2300 5600 50  0001 C CNN
	1    2300 5600
	0    -1   -1   0   
$EndComp
$Comp
L Device:C C1
U 1 1 627E7E68
P 2300 5050
F 0 "C1" V 2048 5050 50  0000 C CNN
F 1 "100n" V 2139 5050 50  0000 C CNN
F 2 "Capacitor_THT:C_Rect_L4.6mm_W2.0mm_P2.50mm_MKS02_FKP02" H 2338 4900 50  0001 C CNN
F 3 "~" H 2300 5050 50  0001 C CNN
	1    2300 5050
	1    0    0    -1  
$EndComp
$Comp
L Device:D D1
U 1 1 627E8502
P 2000 4700
F 0 "D1" V 1954 4780 50  0000 L CNN
F 1 "4148" V 2045 4780 50  0000 L CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 2000 4700 50  0001 C CNN
F 3 "~" H 2000 4700 50  0001 C CNN
	1    2000 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:D D2
U 1 1 627E9467
P 2600 4700
F 0 "D2" V 2554 4780 50  0000 L CNN
F 1 "4148" V 2645 4780 50  0000 L CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 2600 4700 50  0001 C CNN
F 3 "~" H 2600 4700 50  0001 C CNN
	1    2600 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:R R1
U 1 1 627EA667
P 2000 4350
F 0 "R1" H 2070 4396 50  0000 L CNN
F 1 "10M" H 2070 4305 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1930 4350 50  0001 C CNN
F 3 "~" H 2000 4350 50  0001 C CNN
	1    2000 4350
	0    -1   -1   0   
$EndComp
$Comp
L Device:R R2
U 1 1 627EAD72
P 2600 4350
F 0 "R2" H 2670 4396 50  0000 L CNN
F 1 "10M" H 2670 4305 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2530 4350 50  0001 C CNN
F 3 "~" H 2600 4350 50  0001 C CNN
	1    2600 4350
	0    -1   -1   0   
$EndComp
$Comp
L Transistor_FET:BS170 Q1
U 1 1 627EB2A3
P 2300 4000
F 0 "Q1" H 2504 4046 50  0000 L CNN
F 1 "BS170" H 2504 3955 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 2500 3925 50  0001 L CIN
F 3 "https://www.onsemi.com/pub/Collateral/BS170-D.PDF" H 2300 4000 50  0001 L CNN
	1    2300 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	2300 5400 2300 5200
Wire Wire Line
	2300 4900 2300 4700
Wire Wire Line
	2300 4700 2150 4700
Wire Wire Line
	2450 4700 2300 4700
Connection ~ 2300 4700
Wire Wire Line
	2300 4700 2300 4350
Wire Wire Line
	2150 4350 2300 4350
Wire Wire Line
	2300 4350 2450 4350
Connection ~ 2300 4350
Wire Wire Line
	2750 4700 2750 4350
Wire Wire Line
	2300 4350 2300 4200
$Comp
L power:+12V #PWR0101
U 1 1 627ECBDE
P 1500 5600
F 0 "#PWR0101" H 1500 5450 50  0001 C CNN
F 1 "+12V" H 1515 5773 50  0000 C CNN
F 2 "" H 1500 5600 50  0001 C CNN
F 3 "" H 1500 5600 50  0001 C CNN
	1    1500 5600
	0    -1   -1   0   
$EndComp
Wire Wire Line
	1500 5600 1500 4700
Wire Wire Line
	1500 4700 1850 4700
$Comp
L Device:R R3
U 1 1 627ED835
P 1650 4000
F 0 "R3" H 1720 4046 50  0000 L CNN
F 1 "5.1K" H 1720 3955 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1580 4000 50  0001 C CNN
F 3 "~" H 1650 4000 50  0001 C CNN
	1    1650 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	1850 4350 1800 4350
Wire Wire Line
	1800 4350 1800 4000
Wire Wire Line
	1500 4000 1500 4700
Connection ~ 1500 4700
Wire Wire Line
	1800 4000 1950 4000
Wire Wire Line
	1950 4000 1950 3900
Wire Wire Line
	1950 3900 2100 3900
Connection ~ 1800 4000
$Comp
L Device:CP C2
U 1 1 627EE4BF
P 1950 3350
F 0 "C2" V 2205 3350 50  0000 C CNN
F 1 "10u" V 2114 3350 50  0000 C CNN
F 2 "Capacitor_THT:CP_Radial_D5.0mm_P2.50mm" H 1988 3200 50  0001 C CNN
F 3 "~" H 1950 3350 50  0001 C CNN
	1    1950 3350
	-1   0    0    1   
$EndComp
Wire Wire Line
	1950 3500 1950 3900
Connection ~ 1950 3900
$Comp
L Device:R_POT RV1
U 1 1 627F0CD4
P 2700 3700
F 0 "RV1" H 2630 3654 50  0000 R CNN
F 1 "C5K" H 2630 3745 50  0000 R CNN
F 2 "Potentiometer_THT:Potentiometer_Alps_RK163_Single_Horizontal" H 2700 3700 50  0001 C CNN
F 3 "~" H 2700 3700 50  0001 C CNN
	1    2700 3700
	0    1    1    0   
$EndComp
Wire Wire Line
	2500 3900 2500 3700
Wire Wire Line
	2500 3700 2550 3700
Wire Wire Line
	2850 3700 2850 3850
Wire Wire Line
	2850 3850 2700 3850
Wire Wire Line
	2850 3850 2850 4350
Wire Wire Line
	2850 4350 2750 4350
Connection ~ 2850 3850
Connection ~ 2750 4350
$Comp
L Device:R R4
U 1 1 627F3374
P 2700 3000
F 0 "R4" V 2907 3000 50  0000 C CNN
F 1 "100K" V 2816 3000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2630 3000 50  0001 C CNN
F 3 "~" H 2700 3000 50  0001 C CNN
	1    2700 3000
	0    -1   -1   0   
$EndComp
$Comp
L Connector:AudioJack2 J2
U 1 1 627F3BB4
P 1950 2500
F 0 "J2" H 1770 2483 50  0000 R CNN
F 1 "AudioJack2" H 1770 2574 50  0000 R CNN
F 2 "Custom:Jack_6.35mm_Mono" H 1950 2500 50  0001 C CNN
F 3 "~" H 1950 2500 50  0001 C CNN
	1    1950 2500
	0    1    1    0   
$EndComp
Wire Wire Line
	1950 3200 1950 3000
Wire Wire Line
	2850 3000 2850 3700
Connection ~ 2850 3700
Wire Wire Line
	2550 3000 1950 3000
Connection ~ 1950 3000
Wire Wire Line
	1950 3000 1950 2700
Wire Wire Line
	2750 4700 2750 5350
Connection ~ 2750 4700
Wire Wire Line
	2200 5400 2200 5350
Wire Wire Line
	2200 5350 2750 5350
Wire Wire Line
	2050 2700 2850 2700
Wire Wire Line
	2850 2700 2850 3000
Connection ~ 2850 3000
$Comp
L Device:C C3
U 1 1 62800686
P 4200 5050
F 0 "C3" H 4315 5096 50  0000 L CNN
F 1 "100n" H 4315 5005 50  0000 L CNN
F 2 "Capacitor_THT:C_Rect_L4.6mm_W2.0mm_P2.50mm_MKS02_FKP02" H 4238 4900 50  0001 C CNN
F 3 "~" H 4200 5050 50  0001 C CNN
	1    4200 5050
	1    0    0    -1  
$EndComp
$Comp
L Device:D D3
U 1 1 6280068C
P 3900 4700
F 0 "D3" H 3900 4917 50  0000 C CNN
F 1 "4148" H 3900 4826 50  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 3900 4700 50  0001 C CNN
F 3 "~" H 3900 4700 50  0001 C CNN
	1    3900 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:D D4
U 1 1 62800692
P 4500 4700
F 0 "D4" H 4500 4917 50  0000 C CNN
F 1 "4148" H 4500 4826 50  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 4500 4700 50  0001 C CNN
F 3 "~" H 4500 4700 50  0001 C CNN
	1    4500 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:R R5
U 1 1 62800698
P 3900 4350
F 0 "R5" V 4107 4350 50  0000 C CNN
F 1 "10M" V 4016 4350 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3830 4350 50  0001 C CNN
F 3 "~" H 3900 4350 50  0001 C CNN
	1    3900 4350
	0    -1   -1   0   
$EndComp
$Comp
L Device:R R6
U 1 1 6280069E
P 4500 4350
F 0 "R6" V 4707 4350 50  0000 C CNN
F 1 "10M" V 4616 4350 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 4430 4350 50  0001 C CNN
F 3 "~" H 4500 4350 50  0001 C CNN
	1    4500 4350
	0    -1   -1   0   
$EndComp
$Comp
L Transistor_FET:BS170 Q2
U 1 1 628006A4
P 4200 4000
F 0 "Q2" H 4404 4046 50  0000 L CNN
F 1 "BS170" H 4404 3955 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 4400 3925 50  0001 L CIN
F 3 "https://www.onsemi.com/pub/Collateral/BS170-D.PDF" H 4200 4000 50  0001 L CNN
	1    4200 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	4200 5400 4200 5200
Wire Wire Line
	4200 4900 4200 4700
Wire Wire Line
	4200 4700 4050 4700
Wire Wire Line
	4350 4700 4200 4700
Connection ~ 4200 4700
Wire Wire Line
	4200 4700 4200 4350
Wire Wire Line
	4050 4350 4200 4350
Wire Wire Line
	4200 4350 4350 4350
Connection ~ 4200 4350
Wire Wire Line
	4650 4700 4650 4350
Wire Wire Line
	4200 4350 4200 4200
Wire Wire Line
	3400 4700 3750 4700
$Comp
L Device:R R7
U 1 1 628006BD
P 3550 4000
F 0 "R7" V 3757 4000 50  0000 C CNN
F 1 "5.1K" V 3666 4000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3480 4000 50  0001 C CNN
F 3 "~" H 3550 4000 50  0001 C CNN
	1    3550 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	3750 4350 3700 4350
Wire Wire Line
	3700 4350 3700 4000
Wire Wire Line
	3400 4000 3400 4700
Wire Wire Line
	3700 4000 3850 4000
Wire Wire Line
	3850 4000 3850 3900
Wire Wire Line
	3850 3900 4000 3900
Connection ~ 3700 4000
$Comp
L Device:CP C4
U 1 1 628006CB
P 3850 3350
F 0 "C4" H 3732 3304 50  0000 R CNN
F 1 "10u" H 3732 3395 50  0000 R CNN
F 2 "Capacitor_THT:CP_Radial_D5.0mm_P2.50mm" H 3888 3200 50  0001 C CNN
F 3 "~" H 3850 3350 50  0001 C CNN
	1    3850 3350
	-1   0    0    1   
$EndComp
Wire Wire Line
	3850 3500 3850 3900
Connection ~ 3850 3900
$Comp
L Device:R_POT RV2
U 1 1 628006D3
P 4600 3700
F 0 "RV2" V 4393 3700 50  0000 C CNN
F 1 "C5K" V 4484 3700 50  0000 C CNN
F 2 "Potentiometer_THT:Potentiometer_Alps_RK163_Single_Horizontal" H 4600 3700 50  0001 C CNN
F 3 "~" H 4600 3700 50  0001 C CNN
	1    4600 3700
	0    1    1    0   
$EndComp
Wire Wire Line
	4400 3900 4400 3700
Wire Wire Line
	4400 3700 4450 3700
Wire Wire Line
	4750 3700 4750 3850
Wire Wire Line
	4750 3850 4600 3850
Wire Wire Line
	4750 3850 4750 4350
Wire Wire Line
	4750 4350 4650 4350
Connection ~ 4750 3850
Connection ~ 4650 4350
$Comp
L Device:R R8
U 1 1 628006E1
P 4600 3000
F 0 "R8" V 4807 3000 50  0000 C CNN
F 1 "100K" V 4716 3000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 4530 3000 50  0001 C CNN
F 3 "~" H 4600 3000 50  0001 C CNN
	1    4600 3000
	0    -1   -1   0   
$EndComp
$Comp
L Connector:AudioJack2 J4
U 1 1 628006E7
P 3850 2500
F 0 "J4" V 3836 2688 50  0000 L CNN
F 1 "AudioJack2" V 3927 2688 50  0000 L CNN
F 2 "Custom:Jack_6.35mm_Mono" H 3850 2500 50  0001 C CNN
F 3 "~" H 3850 2500 50  0001 C CNN
	1    3850 2500
	0    1    1    0   
$EndComp
Wire Wire Line
	3850 3200 3850 3000
Wire Wire Line
	4750 3000 4750 3700
Connection ~ 4750 3700
Wire Wire Line
	4450 3000 3850 3000
Connection ~ 3850 3000
Wire Wire Line
	3850 3000 3850 2700
Wire Wire Line
	4650 4700 4650 5350
Connection ~ 4650 4700
Wire Wire Line
	4100 5400 4100 5350
Wire Wire Line
	4100 5350 4650 5350
Wire Wire Line
	3950 2700 4750 2700
Wire Wire Line
	4750 2700 4750 3000
Connection ~ 4750 3000
Wire Wire Line
	3400 4700 3400 5950
Wire Wire Line
	3400 5950 1500 5950
Wire Wire Line
	1500 5950 1500 5600
Connection ~ 3400 4700
Connection ~ 1500 5600
Wire Wire Line
	4750 2700 4750 2100
Wire Wire Line
	2850 2100 2850 2700
Connection ~ 4750 2700
Connection ~ 2850 2700
$Comp
L Device:C C5
U 1 1 6280C6CC
P 6050 5050
F 0 "C5" H 6165 5096 50  0000 L CNN
F 1 "100n" H 6165 5005 50  0000 L CNN
F 2 "Capacitor_THT:C_Rect_L4.6mm_W2.0mm_P2.50mm_MKS02_FKP02" H 6088 4900 50  0001 C CNN
F 3 "~" H 6050 5050 50  0001 C CNN
	1    6050 5050
	1    0    0    -1  
$EndComp
$Comp
L Device:D D5
U 1 1 6280C6D2
P 5750 4700
F 0 "D5" H 5750 4917 50  0000 C CNN
F 1 "4148" H 5750 4826 50  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 5750 4700 50  0001 C CNN
F 3 "~" H 5750 4700 50  0001 C CNN
	1    5750 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:D D6
U 1 1 6280C6D8
P 6350 4700
F 0 "D6" H 6350 4917 50  0000 C CNN
F 1 "4148" H 6350 4826 50  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 6350 4700 50  0001 C CNN
F 3 "~" H 6350 4700 50  0001 C CNN
	1    6350 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:R R9
U 1 1 6280C6DE
P 5750 4350
F 0 "R9" V 5957 4350 50  0000 C CNN
F 1 "10M" V 5866 4350 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 5680 4350 50  0001 C CNN
F 3 "~" H 5750 4350 50  0001 C CNN
	1    5750 4350
	0    -1   -1   0   
$EndComp
$Comp
L Device:R R10
U 1 1 6280C6E4
P 6350 4350
F 0 "R10" V 6557 4350 50  0000 C CNN
F 1 "10M" V 6466 4350 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6280 4350 50  0001 C CNN
F 3 "~" H 6350 4350 50  0001 C CNN
	1    6350 4350
	0    -1   -1   0   
$EndComp
$Comp
L Transistor_FET:BS170 Q3
U 1 1 6280C6EA
P 6050 4000
F 0 "Q3" H 6254 4046 50  0000 L CNN
F 1 "BS170" H 6254 3955 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 6250 3925 50  0001 L CIN
F 3 "https://www.onsemi.com/pub/Collateral/BS170-D.PDF" H 6050 4000 50  0001 L CNN
	1    6050 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	6050 5400 6050 5200
Wire Wire Line
	6050 4900 6050 4700
Wire Wire Line
	6050 4700 5900 4700
Wire Wire Line
	6200 4700 6050 4700
Connection ~ 6050 4700
Wire Wire Line
	6050 4700 6050 4350
Wire Wire Line
	5900 4350 6050 4350
Wire Wire Line
	6050 4350 6200 4350
Connection ~ 6050 4350
Wire Wire Line
	6500 4700 6500 4350
Wire Wire Line
	6050 4350 6050 4200
Wire Wire Line
	5250 4700 5600 4700
$Comp
L Device:R R11
U 1 1 6280C6FC
P 5400 4000
F 0 "R11" V 5607 4000 50  0000 C CNN
F 1 "5.1K" V 5516 4000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 5330 4000 50  0001 C CNN
F 3 "~" H 5400 4000 50  0001 C CNN
	1    5400 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	5600 4350 5550 4350
Wire Wire Line
	5550 4350 5550 4000
Wire Wire Line
	5250 4000 5250 4700
Wire Wire Line
	5550 4000 5700 4000
Wire Wire Line
	5700 4000 5700 3900
Wire Wire Line
	5700 3900 5850 3900
Connection ~ 5550 4000
$Comp
L Device:CP C6
U 1 1 6280C709
P 5700 3350
F 0 "C6" H 5582 3304 50  0000 R CNN
F 1 "10u" H 5582 3395 50  0000 R CNN
F 2 "Capacitor_THT:CP_Radial_D5.0mm_P2.50mm" H 5738 3200 50  0001 C CNN
F 3 "~" H 5700 3350 50  0001 C CNN
	1    5700 3350
	-1   0    0    1   
$EndComp
Wire Wire Line
	5700 3500 5700 3900
Connection ~ 5700 3900
$Comp
L Device:R_POT RV3
U 1 1 6280C711
P 6450 3700
F 0 "RV3" V 6243 3700 50  0000 C CNN
F 1 "C5K" V 6334 3700 50  0000 C CNN
F 2 "Potentiometer_THT:Potentiometer_Alps_RK163_Single_Horizontal" H 6450 3700 50  0001 C CNN
F 3 "~" H 6450 3700 50  0001 C CNN
	1    6450 3700
	0    1    1    0   
$EndComp
Wire Wire Line
	6250 3900 6250 3700
Wire Wire Line
	6250 3700 6300 3700
Wire Wire Line
	6600 3700 6600 3850
Wire Wire Line
	6600 3850 6450 3850
Wire Wire Line
	6600 3850 6600 4350
Wire Wire Line
	6600 4350 6500 4350
Connection ~ 6600 3850
Connection ~ 6500 4350
$Comp
L Device:R R12
U 1 1 6280C71F
P 6450 3000
F 0 "R12" V 6657 3000 50  0000 C CNN
F 1 "100K" V 6566 3000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6380 3000 50  0001 C CNN
F 3 "~" H 6450 3000 50  0001 C CNN
	1    6450 3000
	0    -1   -1   0   
$EndComp
$Comp
L Connector:AudioJack2 J6
U 1 1 6280C725
P 5700 2500
F 0 "J6" V 5686 2688 50  0000 L CNN
F 1 "AudioJack2" V 5777 2688 50  0000 L CNN
F 2 "Custom:Jack_6.35mm_Mono" H 5700 2500 50  0001 C CNN
F 3 "~" H 5700 2500 50  0001 C CNN
	1    5700 2500
	0    1    1    0   
$EndComp
Wire Wire Line
	5700 3200 5700 3000
Wire Wire Line
	6600 3000 6600 3700
Connection ~ 6600 3700
Wire Wire Line
	6300 3000 5700 3000
Connection ~ 5700 3000
Wire Wire Line
	5700 3000 5700 2700
Wire Wire Line
	6500 4700 6500 5350
Connection ~ 6500 4700
Wire Wire Line
	5950 5400 5950 5350
Wire Wire Line
	5950 5350 6500 5350
Wire Wire Line
	5800 2700 6600 2700
Wire Wire Line
	6600 2700 6600 3000
Connection ~ 6600 3000
Connection ~ 5250 4700
Wire Wire Line
	6600 2700 6600 2100
Connection ~ 6600 2700
Wire Wire Line
	2850 2100 4750 2100
$Comp
L Device:C C7
U 1 1 62810C6D
P 7950 5050
F 0 "C7" H 8065 5096 50  0000 L CNN
F 1 "100n" H 8065 5005 50  0000 L CNN
F 2 "Capacitor_THT:C_Rect_L4.6mm_W2.0mm_P2.50mm_MKS02_FKP02" H 7988 4900 50  0001 C CNN
F 3 "~" H 7950 5050 50  0001 C CNN
	1    7950 5050
	1    0    0    -1  
$EndComp
$Comp
L Device:D D7
U 1 1 62810C73
P 7650 4700
F 0 "D7" H 7650 4917 50  0000 C CNN
F 1 "4148" H 7650 4826 50  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 7650 4700 50  0001 C CNN
F 3 "~" H 7650 4700 50  0001 C CNN
	1    7650 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:D D8
U 1 1 62810C79
P 8250 4700
F 0 "D8" H 8250 4917 50  0000 C CNN
F 1 "4148" H 8250 4826 50  0000 C CNN
F 2 "Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal" H 8250 4700 50  0001 C CNN
F 3 "~" H 8250 4700 50  0001 C CNN
	1    8250 4700
	1    0    0    -1  
$EndComp
$Comp
L Device:R R13
U 1 1 62810C7F
P 7650 4350
F 0 "R13" V 7857 4350 50  0000 C CNN
F 1 "10M" V 7766 4350 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 7580 4350 50  0001 C CNN
F 3 "~" H 7650 4350 50  0001 C CNN
	1    7650 4350
	0    -1   -1   0   
$EndComp
$Comp
L Device:R R14
U 1 1 62810C85
P 8250 4350
F 0 "R14" V 8457 4350 50  0000 C CNN
F 1 "10M" V 8366 4350 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 8180 4350 50  0001 C CNN
F 3 "~" H 8250 4350 50  0001 C CNN
	1    8250 4350
	0    -1   -1   0   
$EndComp
$Comp
L Transistor_FET:BS170 Q4
U 1 1 62810C8B
P 7950 4000
F 0 "Q4" H 8154 4046 50  0000 L CNN
F 1 "BS170" H 8154 3955 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 8150 3925 50  0001 L CIN
F 3 "https://www.onsemi.com/pub/Collateral/BS170-D.PDF" H 7950 4000 50  0001 L CNN
	1    7950 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	7950 5400 7950 5200
Wire Wire Line
	7950 4900 7950 4700
Wire Wire Line
	7950 4700 7800 4700
Wire Wire Line
	8100 4700 7950 4700
Connection ~ 7950 4700
Wire Wire Line
	7950 4700 7950 4350
Wire Wire Line
	7800 4350 7950 4350
Wire Wire Line
	7950 4350 8100 4350
Connection ~ 7950 4350
Wire Wire Line
	8400 4700 8400 4350
Wire Wire Line
	7950 4350 7950 4200
Wire Wire Line
	7150 4700 7500 4700
$Comp
L Device:R R15
U 1 1 62810C9D
P 7300 4000
F 0 "R15" V 7507 4000 50  0000 C CNN
F 1 "5.1K" V 7416 4000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 7230 4000 50  0001 C CNN
F 3 "~" H 7300 4000 50  0001 C CNN
	1    7300 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	7500 4350 7450 4350
Wire Wire Line
	7450 4350 7450 4000
Wire Wire Line
	7150 4000 7150 4700
Wire Wire Line
	7450 4000 7600 4000
Wire Wire Line
	7600 4000 7600 3900
Wire Wire Line
	7600 3900 7750 3900
Connection ~ 7450 4000
$Comp
L Device:CP C8
U 1 1 62810CAA
P 7600 3350
F 0 "C8" H 7482 3304 50  0000 R CNN
F 1 "10u" H 7482 3395 50  0000 R CNN
F 2 "Capacitor_THT:CP_Radial_D5.0mm_P2.50mm" H 7638 3200 50  0001 C CNN
F 3 "~" H 7600 3350 50  0001 C CNN
	1    7600 3350
	-1   0    0    1   
$EndComp
Wire Wire Line
	7600 3500 7600 3900
Connection ~ 7600 3900
$Comp
L Device:R_POT RV4
U 1 1 62810CB2
P 8350 3700
F 0 "RV4" V 8143 3700 50  0000 C CNN
F 1 "C5K" V 8234 3700 50  0000 C CNN
F 2 "Potentiometer_THT:Potentiometer_Alps_RK163_Single_Horizontal" H 8350 3700 50  0001 C CNN
F 3 "~" H 8350 3700 50  0001 C CNN
	1    8350 3700
	0    1    1    0   
$EndComp
Wire Wire Line
	8150 3900 8150 3700
Wire Wire Line
	8150 3700 8200 3700
Wire Wire Line
	8500 3700 8500 3850
Wire Wire Line
	8500 3850 8350 3850
Wire Wire Line
	8500 3850 8500 4350
Wire Wire Line
	8500 4350 8400 4350
Connection ~ 8500 3850
Connection ~ 8400 4350
$Comp
L Device:R R16
U 1 1 62810CC0
P 8350 3000
F 0 "R16" V 8557 3000 50  0000 C CNN
F 1 "100K" V 8466 3000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 8280 3000 50  0001 C CNN
F 3 "~" H 8350 3000 50  0001 C CNN
	1    8350 3000
	0    -1   -1   0   
$EndComp
$Comp
L Connector:AudioJack2 J8
U 1 1 62810CC6
P 7600 2500
F 0 "J8" V 7586 2688 50  0000 L CNN
F 1 "AudioJack2" V 7677 2688 50  0000 L CNN
F 2 "Custom:Jack_6.35mm_Mono" H 7600 2500 50  0001 C CNN
F 3 "~" H 7600 2500 50  0001 C CNN
	1    7600 2500
	0    1    1    0   
$EndComp
Wire Wire Line
	7600 3200 7600 3000
Wire Wire Line
	8500 3000 8500 3700
Connection ~ 8500 3700
Wire Wire Line
	8200 3000 7600 3000
Connection ~ 7600 3000
Wire Wire Line
	7600 3000 7600 2700
Wire Wire Line
	8400 4700 8400 5350
Wire Wire Line
	8400 5350 8550 5350
Connection ~ 8400 4700
$Comp
L power:GND #PWR0102
U 1 1 62810CD5
P 8550 5350
F 0 "#PWR0102" H 8550 5100 50  0001 C CNN
F 1 "GND" H 8555 5177 50  0000 C CNN
F 2 "" H 8550 5350 50  0001 C CNN
F 3 "" H 8550 5350 50  0001 C CNN
	1    8550 5350
	0    -1   -1   0   
$EndComp
Wire Wire Line
	7850 5400 7850 5350
Wire Wire Line
	7850 5350 8400 5350
Connection ~ 8400 5350
Wire Wire Line
	7700 2700 8500 2700
Wire Wire Line
	8500 2700 8500 3000
Connection ~ 8500 3000
Wire Wire Line
	7150 4700 7150 5950
Connection ~ 7150 4700
Wire Wire Line
	8500 2700 8500 2100
Wire Wire Line
	8500 2100 6600 2100
Connection ~ 8500 2700
Wire Wire Line
	7150 5950 5250 5950
Wire Wire Line
	3400 5950 5250 5950
Connection ~ 3400 5950
Connection ~ 5250 5950
Wire Wire Line
	5250 5950 5250 4700
Connection ~ 4750 2100
Wire Wire Line
	4750 2100 6600 2100
Connection ~ 6600 2100
$Comp
L Connector_Generic:Conn_02x05_Top_Bottom J9
U 1 1 62879E99
P 9750 2300
F 0 "J9" H 9800 2717 50  0000 C CNN
F 1 "Conn_02x05_Top_Bottom" H 9800 2626 50  0000 C CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_2x05_P2.54mm_Vertical" H 9750 2300 50  0001 C CNN
F 3 "~" H 9750 2300 50  0001 C CNN
	1    9750 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	9550 2200 9550 2300
Connection ~ 9550 2300
Wire Wire Line
	10050 2400 10050 2300
Wire Wire Line
	10050 2300 10050 2200
Connection ~ 10050 2300
Wire Wire Line
	10050 2200 9550 2200
Connection ~ 10050 2200
Connection ~ 9550 2200
Wire Wire Line
	9550 2300 9550 2400
Wire Wire Line
	9550 2400 10050 2400
Connection ~ 9550 2400
Connection ~ 10050 2400
Wire Wire Line
	10050 2100 9550 2100
$Comp
L power:+12V #PWR0103
U 1 1 628A2AAF
P 9200 2100
F 0 "#PWR0103" H 9200 1950 50  0001 C CNN
F 1 "+12V" H 9215 2273 50  0000 C CNN
F 2 "" H 9200 2100 50  0001 C CNN
F 3 "" H 9200 2100 50  0001 C CNN
	1    9200 2100
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0104
U 1 1 628A39EC
P 10400 2300
F 0 "#PWR0104" H 10400 2050 50  0001 C CNN
F 1 "GND" H 10405 2127 50  0000 C CNN
F 2 "" H 10400 2300 50  0001 C CNN
F 3 "" H 10400 2300 50  0001 C CNN
	1    10400 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	10400 2300 10050 2300
Wire Wire Line
	9550 2100 9200 2100
Connection ~ 9550 2100
$Comp
L Connector:AudioJack2_SwitchT J3
U 1 1 629100C4
P 4200 5600
F 0 "J3" V 4278 5370 50  0000 R CNN
F 1 "AudioJack2_SwitchT" V 4187 5370 50  0000 R CNN
F 2 "Custom:Jack_6.35mm_MonoSwitch" H 4200 5600 50  0001 C CNN
F 3 "~" H 4200 5600 50  0001 C CNN
	1    4200 5600
	0    -1   -1   0   
$EndComp
Wire Wire Line
	2300 5400 3950 5400
Wire Wire Line
	3950 5400 3950 5800
Wire Wire Line
	3950 5800 4500 5800
Wire Wire Line
	4500 5800 4500 5400
Wire Wire Line
	4500 5400 4300 5400
Connection ~ 2300 5400
$Comp
L Connector:AudioJack2_SwitchT J5
U 1 1 6292F0C0
P 6050 5600
F 0 "J5" V 6128 5370 50  0000 R CNN
F 1 "AudioJack2_SwitchT" V 6037 5370 50  0000 R CNN
F 2 "Custom:Jack_6.35mm_MonoSwitch" H 6050 5600 50  0001 C CNN
F 3 "~" H 6050 5600 50  0001 C CNN
	1    6050 5600
	0    -1   -1   0   
$EndComp
$Comp
L Connector:AudioJack2_SwitchT J7
U 1 1 62930202
P 7950 5600
F 0 "J7" V 8028 5370 50  0000 R CNN
F 1 "AudioJack2_SwitchT" V 7937 5370 50  0000 R CNN
F 2 "Custom:Jack_6.35mm_MonoSwitch" H 7950 5600 50  0001 C CNN
F 3 "~" H 7950 5600 50  0001 C CNN
	1    7950 5600
	0    -1   -1   0   
$EndComp
Wire Wire Line
	4500 5800 6400 5800
Wire Wire Line
	6400 5800 6400 5400
Wire Wire Line
	6400 5400 6150 5400
Connection ~ 4500 5800
Wire Wire Line
	6400 5800 8350 5800
Wire Wire Line
	8350 5800 8350 5400
Wire Wire Line
	8350 5400 8050 5400
Connection ~ 6400 5800
$EndSCHEMATC
