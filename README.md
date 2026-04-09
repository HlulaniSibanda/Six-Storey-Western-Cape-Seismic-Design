# Six-Storey-Western-Cape-Seismic-Design
This project features the seismic design of a sex storey building located in Western Cape South Africa. SANS codes under the SANS 10160 suite have been used in the designing of this building, to ensure that is not only safe but also adheres to South African standards
![Lucid_Origin_a_cinematic_photo_of_a_7_storey_building_with_lar_0](https://github.com/user-attachments/assets/27a9c9fe-876e-40a7-9ee4-8c0642a4f9f8)

											
	Note: Calculations according to SANS codes										
	This includes calculating the self-weight of the structural elements (M25/M30 concrete), the superimposed dead loads (brick walls, 12 mm plaster, floor finishes, waterproofing), and the imposed (live) loads based on the building's use as a commercial/exhibition space										
											
											
											
	Unit Load Calcultions										
	Calculations according to SANS 10160-2										
	Assumed sizes of beam and column sections are:										
											
	Columns: 	500 x 500 mm at all typical floors									
		Area = 0.25m^2 , I = 0.005208m^4									
											
	Columns:	600 x 600 mm below ground level									
		Area = 0.36m^2, I = 0.0108m^4 									
											
	Main beams: 300 x 600 mm at all floors										
		Area = 0.18 m^2, I = 0.0054m^4									
											
	Ground beams: 300 x 600 mm 										
		Area = 0.18 m^2, I = 0.0054m^4									
											
	Secondary beams: 200 x 600 										
		Area = 0.12m^2, I = 0.0036m^4									
											
	Member self-weights										
											
	Columns at all typical floors:										
	w = 0.5m x 0.5m x 25kN/m^3 = 6.25kN/m										
											
	Columns below ground level:										
	w = 0.6m x 0.6m x 25kN/m^3 = 9kN/m										
											
	Main beams at all floors:										
	w = 0.3m x 0.6m x 25kN/m^3 = 4.5kN/m										
											
	Ground beams: 										
	w = 0.3m x 0.6m x 25kN/m^3 = 4.5kN/m										
											
	Secondary beams: 										
	w = 0.2m x 0.6m x 25kN/m^3  = 3kN/m										
											
	Slab (100mm thick):										
	0.1m x 25kN/m^3 = 2.5kN/m^2 										
											
	Brick wall (230mm thick)										
	w = 0.230m x 19kN/m3 + 2 x 0.012m x 23kN/m^3 = 4.922kN/m2										
											
	Floor wall (4.4m height):										
	w = 4.4m x brick wall self-weight = 4.4m x 4.922kN/m^2 = 21.66kN/m										
											
	Ground floor wall (3.5m height):										
	w = 3.5m x 4.922kN/m^2 =17.23kN/m										
											
	Underground floor wall (0.7m height):										
	w = 0.7m x 4.922kN/m^2 = 3.445kN/m										
											
	Terrace parampet (1m height)										
	w = 1m x 4.922kN/m^2 = 4.922kN/m										
											
	Slab Load Calculations:										
											
	Component	Terrace 	Typical								
		DL + LL (kN/m^2)	DL + LL (kN/m^2)								
	Self (100mm thick)	2.5 + 0	2.5 + 0								
	Water Proofing	2 + 0	0 + 0								
	Floor Finish 	1 + 0	1 + 0								
	Live Load	0 + 1.5 	0 + 4 								
	Total 	5.5 + 1.5 	3.5 + 4								
											
	Beam and Frame Load Calculations										
											
	[1] Terrace level:										
	Floor beams:										
	From slab: 										
	w = ( 1.25m + 1.25m) x (5.5 kN/m^2+ 1.5kN/m^2) = (13.75 + 3.75) kN/m										
	Self-weight (Secondary rib beams) = 2.5 + 0 kN/m										
	Total = 	(16.25 + 3.75) kN/m									
	Reaction on main beam:  R=wL/2										
	R = 0.5 x 7.5 x (16.25 + 3.75) = (60.94 + 14.06)kN										
											
	Main Beams B1-B2-B3 and B10-B11-B12										
											
	Component	B1-B3 		B2							
	From slab:										
	R = wL/2 			0 + 0							
	R = 0.5 x 2.5m x (5.5 + 1.5)kN/m^2  			Beams parallel to slab span							
	R = 6.875kN/m + 1.875kN/m										
	From parapet:										
	R = wL/2 										
	R = 4.922kN/m + 0			R = 4.922kN/m + 0							
	Total:	(11.8 + 1.875) kN/m		(4.922 + 0) kN/m							
											
	From secondary beams:										
	Two point loads at 2.5m from the two edges, for beams B2 and B11 of (61.1 + 14.3)kN from the secondary beams (F.B's)***										
											
	Main Beams B4-B5-B6, B7-B8-B9, B16-B17-B18, and B19-B20-B21										
											
	From slab:										
	R = wL/2 										
	R = 0.5 x 2.5m x (5.5 + 1.5)kN/m^2  										
	R = 6.875kN/m + 1.875kN/m										
											
	From secondary beams:										
	Two point loads at 2.5m from the two edges, on all of the main beams mentioned above, of (61.1 + 14.3)kN from the secondary beams (F.B's)***										
											
	Main Beams B13-B14-B15 and B22-B23-B24										
											
	Component	B13-B15 & B22-B24		B14 & B23							
	From slab:										
		0 + 0		R = wL/2 							
				R = 0.5 x 2.5m x (5.5 + 1.5)kN/m^2  							
				R = 6.875kN/m + 1.875kN/m							
	From parapet:										
	R = wL/2 										
	R = 4.922kN/m + 0			R = 4.922kN/m + 0							
	Total:	(4.922 + 0) kN/m		(11.8 + 1.875) kN/m							
											
	From secondary beams:										
	Two point loads at 2.5m from the two edges, on beams B13,B15,B22, and B24, of (61.1 + 14.3)kN from the secondary beams (F.B's)***										
											
	[2] Floor level										
	Floor beams:										
	From slab:										
	w = (1.25 + 1.25)m x (3.5 + 4)kN/m^2 = (8.75 + 10)kN/m										
	Self-weight (Secondary rib beams)   = 2.5 + 0 kN/m										
	Total                                                           = (11.25 + 10)kN/m										
											
	Reaction on main beam:										
	R = wL/2 = 0.5 x 7.5 x (11.25 + 10) = (42.19 + 37.5)kN				<< Point load from secondary beam						
											
	Main beams B1-B2-B3 and B10-B11-B12										
											
	Component	B1-B3 & B10-B12	B2 & B11								
	From slab		0 + 0								
	R =wL/2 =0.5 x 2.5 x (3.5 + 4)										
	R = (4.375 +5)kN/m										
	From wall										
	w = 21.66kN/m + 0		w = 21.66kN/m + 0								
											
	From secondary beams:										
	Two point loads at 2.5m from the two edges, on beams B2 and B11, of (42.19 + 37.5)kN from the secondary beams (F.B's)***										
											
	Main beams B4-B5-B6, B7-B8-B9, B16-B17-B18, and B19-B20-B21										
											
	From slab:										
	R = wL/2 = 0.5 x 2.5 x (3.5 + 4)										
	R = (4.375 + 5)kN/m		All beams carry slab loads because they are internal beams								
											
	From secondary beams:										
	Two point loads on all beams at 2.5m from the two edges, of (42.19 + 37.5)kN from the secondary beams (F.B's)***										
											
	Main beams B13-B14-B15 and B22-B23-B24										
											
	Component	B14 & B23	B13-B15 & B22-B24								
	From slab		0 + 0								
	R =wL/2 =0.5 x 2.5 x (3.5 + 4)										
	R = (4.375 +5)kN/m										
	From wall										
	w = 21.66kN/m + 0		w = 21.66kN/m + 0								
	Total 	26.04kN/m + 5kN/m	21.66kN/m								
											
	From secondary beams:										
	Two point loads on beams B13-B15 and B22-B24 at 2.5m from the two edges, of (42.19 + 37.5)kN from the secondary beams (F.B's)***										
											
	[3] Ground Level										
	Floor beams:										
	No floor beams on ground level										
											
	Reaction on main beam:										
	R = wL/2 = 0.5 x 7.5 x (0 + 0) = (0 + 0)kN										
											
	Outer Beams: B1-B2-B3, B10-B11-B12, B13-B14-B15-B16, and B22-B23-B24										
											
	Wall Load: w = 3.5m x 4.922kN/m^2 =17.23kN/m										
											
	"Inner beams: B4-B5-B6; B7-B8-B9; B16-
B17-B18 and B19-B20-B21"										
											
	Wall Load: w = 0.7m x 4.922kN/m^2 =3.45kN/m										
											
<img width="1355" height="4547" alt="image" src="https://github.com/user-attachments/assets/63d502ca-e19e-4258-a959-1400a241314d" />

				
	Loading Frames			
	According to SANS 10160-2 , Clause 9.3.1.11 			
				
	1) Indentifying occupancy category:			
				
	According to the description, this building fall under sub-category C3 			
	Where qk (LL) = 5kN/m2 and Qk(DL) = 300kN/m2 			
				
	2) Calculating the loaded area (A):			
				
	Tributary are per floor = 7.5m x 7.5m = 56.25m2			
	Cumulative loaded area (A) =  5 floors x Tributary area per floor 			
	                                              A  = 5 x 56.25m2			
	                                                 A = 281.25m2			
				
	3) Area reduction factor @A			
	For occupancy categories C & D			
				
	Area reduction factor @A = 0.5 + 4.5/SQRT(A)			
	Area reduction factor @A = 0.5 + 4.5/SQRT(281.25)			
	Area reduction factor @A = 0.768 >= 0.7  therefore O.K			
				
	Therefore 23.2% reduction in the live load the columns need to be designed for			
	Ed = 1.2Gk + 1.6(0.78 x qk)			
				
<img width="1018" height="660" alt="image" src="https://github.com/user-attachments/assets/e5974eed-2310-4ef7-80f4-dd13c6f93fcf" />

														
	Seismic Weight Calculations													
														
	Following reduced live loads for seismic mass analysis: Zero (0%) on terrace, and 30% on other floors [ SANS 10160-1:2011, Clause 7.3.5.1 & Table 2]													
														
	(1) Storey 7 - Tarrace:													
			                    DL + LL											
	From slab: 22.5 x 22.5 (5.5 + 0) = 2784.38kN + 0													
	Parapet: 4 x 22.5 (4.9 + 0) = 441kN + 0													
	Walls: 0.5 x 4 x 22.5 (21.66+ 0) = 974.7kN + 0													
	Secondary beams: 18 x 7.5 x (3 + 0) = 405kN													
	Main beams: 8 x 22.5 x (4.5 + 0) = 810kN + 0													
	Columns: 0.5 x 5 x 16 x  ( 6.25 + 0) = 250kN + 0													
	Total 		5176.40kN											
														
	(2) Storeys 6,5,4, and, 3													
			                    DL + LL											
	From slab: 22.5 x 22.5 x (3.5 + 0.3 x 4) = 1771.88kN + 607.50kN													
	Walls: 4 x 22.5 x (21.66 + 0) = 1949.40kN + 0 													
	Secondary beams: 18 x 7.5 x (3 + 0) = 405kN													
	Main beams: 8 x 22.5 x (4.5 + 0) = 810kN + 0													
	Columns: 5 x 16 x  ( 6.25 + 0) = 500kN + 0													
	Total			5436.28 + 607.50										
				6043.78kN										
														
	(3) Storey 2													
			                    DL + LL											
	From slab: 22.5 x 22.5 x (3.5 + 0.3 x 4) = 1771.88kN + 607.50kN													
	Walls: 0.5 x 4 x 22.5 x (21.66 + 0) = 974.7kN + 0													
	Walls: 0.5 x 4 x 22.5 x (17.23 + 0) = 775.35kN + 0 													
	Secondary beams: 18 x 7.5 x (3 + 0) = 405kN													
	Main beams: 8 x 22.5 x (4.5 + 0) = 810kN + 0													
	Columns: 0.5 x 5 x 16 x  ( 6.25 + 0) = 250kN + 0													
	Columns: 0.5 x 4.1 x 16 x  ( 6.25 + 0) = 205kN + 0													
	Total			5191.93 + 607.50										
				5799.43kN										
														
	(1) Storey 1 (Plinth)													
			                    DL + LL											
	Walls: 0.5 x 4 x 22.5 x (3.45+ 0) = 155.25kN + 0													
	Walls: 0.5 x 4 x 22.5 x (17.23 + 0) = 775.35kN + 0 													
	Main beams: 8 x 22.5 x (4.5 + 0) = 810kN + 0													
	Columns: 0.5 x 1.1 x 16 x  ( 9 + 0) = 79.2kN + 0													
	Columns: 0.5 x 4.1 x 16 x  ( 6.25 + 0) = 205kN + 0													
	Total			2024.8kN										
														
	Seismic Weight of Entire Building													
														
	B = 5176.40 + 6043.78 + 5799.43 + 2024.8													
	B = 37175.75kN													
<img width="1281" height="1238" alt="image" src="https://github.com/user-attachments/assets/31652b5b-b2d9-4358-a043-559639470b4c" />

												
	Design Seismic Load											
												
	Design follows SANS 10160 -4 : 2009											
	The infill walls in upper floors may contain large openings, although the solid walls are considered											
	in load calculations. Therefore, fundamental time period T is obtained by using the following formula according to Clause 7.5.2.1:											
	T = CT x ht^(3/4) where CT = 0.075 for reinforced concrete moment resisting frames											
	T = 0.075 x 30.5 ^(3/4)											
	T = 0.97 seconds											
												
	Assuming zone I seismic activity for the Western Cape area											
												
	ag = 0.10g											
	Importance class III --> Y = 1.2 											
	Ground type 3 											
	Soil factor = 1.15											
	Tc = 0.6 sec											
	TD = 2.0 sec											
	q = 3.0											
	Normalised design response spectrum Sd(T):											
	Clause 4.3:											
	Because T(0.97) falls between TC(0.65) and TD(2.0) equation 3 will be used:											
												
	Sd(T) = ag x S x (2.5/q) x [Tc/T]											
	Sd(T) = 0.1 x 1.15 x (2.5/3) x [0.6/0.97]											
	Sd(T) = 0.059											
	Verifying this result against the lower bound limit B x ag											
	B = 0.2  There fore 0.2 x 0.1 = 0.02 											
	The calculated Sd(T) value is acceptable											
<img width="1169" height="732" alt="image" src="https://github.com/user-attachments/assets/4d01e08c-341f-40df-978d-9df92a6db091" />

															
	Table 1: Distribution of Total Horizontal  Loads To Each Floor														
															
	Storey	Wi (kN)	hi (m)	Wi x hi^2 x 10^-3	Qi =[ (Wi x hi^2) / SUM(Wi x hi^2)] x Ed,base (kN)	Vi (kN)									
	7	5176.4	30.2	4721.083856	940.68	940.6823827									
	6	6043.78	25.2	3838.042051	764.74	1705.42									
	5	6043.78	20.2	2466.103991	491.37	2196.79									
	4	6043.78	15.2	1396.354931	278.23	2475.02									
	3	6043.78	10.2	628.7948712	125.29	2600.31									
	2	5799.43	5.2	156.8165872	31.25	2631.55									
	1	2024.8	1.1	2.450008	0.49	2632.04									
	Total	37175.75	107.3	13209.6463	2632.04	15181.80735									
															
	Nominal Base Shear (Vn):														
	SANS 10160-4:2009 Clause 7.5.1 eqution 10:														
	Vn = Sd(T) x Wn														
	Vn = 0.059 x 37175.75														
	Vn = 2193.37kN														
															
	Factored Design Base Shear:														
	Yi = 1.2														
	p = 1 														
	Ed,base = Vn x Yi x p														
	Ed,base = 2193.37 x 1.2 x 1														
	Ed,base = 2632.04kN														
															
	The design base shear force of 2 632.04 kN is now distributed along the height of the building as per clause 7.5.3 of SANS 10160-4:2009. This distribution is shown in Table 1.														
															
<img width="1481" height="756" alt="image" src="https://github.com/user-attachments/assets/87409657-508e-4dfb-8660-a0e0ae7f4757" />

														
	Accidental Eccentricity Design													
														
	According to SANS 10160-4:2009 Clause 7.5.4.3:													
	The formula for accidental eccentricity is given by : ed = es +/- 0.05L													
	where													
	es = structural (static) eccentricity, which is the distance between the centre of mass and the centre of stiffness													
	L = dimension of the building perpendicular to the direction of the applied forces													
														
	Since the building is symmetrical on all sides, es = 0													
	L = 22.5m													
	ed = +/-0.05(22.5)													
	ed = +/- 1.125m													
														
	Since the centre of mass and the centre of stiffness coincide in the present case, the eccentricity from the centre of stiffness is also1.125m													
	Therefore the laterl for Qi acts at the centre of stiffness accompanied by a clockwise or anti-clowise torsional moment (+1.125 Qi kNm or -1.125 Qi kNm)													
														
	Note that the building structure is identical along the X- and Z- directions, and hence, the fundamental time period and the earthquake													
	forces are the same in the two directions.													
														
	Torsinal Moments 													
	Storey	Lateral Force Qi (kN)	Design eccentricity ed (m)	Torsional Moment (kNm)										
	7	940.68	1.125	1058.267681										
	6	764.74	1.125	860.3269891										
	5	491.37	1.125	552.7963981										
	4	278.23	1.125	313.0038227										
	3	125.29	1.125	140.949263										
	2	31.25	1.125	35.15165819										
	1	0.49	1.125	0.549188356										
<img width="1349" height="780" alt="image" src="https://github.com/user-attachments/assets/9fbac824-2394-431b-a349-8182f5d419be" />


<img width="862" height="1248" alt="Lateral forces and torsional moments v2" src="https://github.com/user-attachments/assets/6b47f241-cbbe-4d94-a5da-db4956011764" />
