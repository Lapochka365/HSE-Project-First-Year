The dataset can be downloaded from two sources:

- from local folder on [_GDrive_](https://drive.google.com/drive/folders/1v4eVCl17TgRtizqfyTbFOan8NhcYlve8?usp=sharing)
- from source site of [_University of Leicester_](https://leicester.figshare.com/articles/dataset/Myocardial_infarction_complications_Database/12045261/3)

One of the things to point out is that authors of the dataset specified the usage of features depending on how we want to proceed with our __classification of complications__:
- __the time of admission to hospital__: all input columns (2-112) except 93, 94, 95, 100, 101, 102, 103, 104, 105 can be used for prediction;
- __the end of the first day__ (24 hours after admission to the hospital): all input columns (2-112) except 94, 95, 101, 102, 104, 105 can be used for prediction;
- __the end of the second day__ (48 hours after admission to the hospital) all input columns (2-112) except 95, 102, 105 can be used for prediction;
- __the end of the third day__ (72 hours after admission to the hospital) all input columns (2-112) can be used for prediction.

__Features descriptions__:
1. Record ID (ID).
2. Age (AGE).
3. Gender (SEX): 0 – female 1 – male
4. Quantity of myocardial infarctions in the anamnesis (INF_ANAM): 0 – zero 1 – one 2 – two 3 – three and more
5. Exertional angina pectoris in the anamnesis (STENOK_AN): 0 – never 1 – during the last year 2 – one year ago 3 – two years ago 4 – three years ago 5 – 4-5 years ago 6 – more than 5 years ago
6. Functional class (FC) of angina pectoris in the last year (FK_STENOK)[2]: 0 – there is no angina pectoris 1 – I FC 2 – II FC 3 – III FC. 4 – IV FC
7. Coronary heart disease (CHD) in recent weeks, days before admission to hospital (IBS_POST): 0 – there was no СHD 1 – exertional angina pectoris 2 – unstable angina pectoris
8. Heredity on CHD (IBS_NASL): 0 – isn’t burdened 1 – burdened
9. Presence of an essential hypertension (GB): 0 – there is no essential hypertension 1 – Stage 1 2 – Stage 2 3 – Stage 3
10. Symptomatic hypertension (SIM_GIPERT): 0 – no 1 – yes
11. Duration of arterial hypertension (DLIT_AG): 0 – there was no arterial hypertension 1 – one year 2 – two years 3 – three years 4 – four years 5 – five years 6 – 6-10 years 7 – more than 10 years
12. Presence of chronic Heart failure (HF) in the anamnesis (ZSN_A): 0 – there is no chronic heart failure 1 – I stage 2 – IIА stage (heart failure due to right ventricular systolic dysfunction) 3 – IIА stage (heart failure due to left ventricular systolic dysfunction) 4 – IIB stage (heart failure due to left and right ventricular systolic dysfunction)
13. Observing of arrhythmia in the anamnesis (nr11): 0 – no 1 – yes
14. Premature atrial contractions in the anamnesis (nr01): 0 – no 1 – yes
15. Premature ventricular contractions in the anamnesis (nr02): 0 – no 1 – yes
16. Paroxysms of atrial fibrillation in the anamnesis (nr03): 0 – no 1 – yes
17. A persistent form of atrial fibrillation in the anamnesis (nr04): 0 – no 1 – yes
18. Ventricular fibrillation in the anamnesis (nr07): 0 – no 1 – yes
19. Ventricular paroxysmal tachycardia in the anamnesis (nr08): 0 – no 1 – yes
20. First-degree AV block in the anamnesis (np01): 0 – no 1 – yes
21. Third-degree AV block in the anamnesis (np04): 0 – no 1 – yes
22. LBBB (anterior branch) in the anamnesis (np05): 0 – no 1 – yes
23. Incomplete LBBB in the anamnesis (np07): 0 – no 1 – yes
24. Complete LBBB in the anamnesis (np08): 0 – no 1 – yes
25. Incomplete RBBB in the anamnesis (np09): 0 – no 1 – yes
26. Complete RBBB in the anamnesis (np10): 0 – no 1 – yes
27. Diabetes mellitus in the anamnesis (endocr_01): 0 – no 1 – yes
28. Obesity in the anamnesis (endocr_02): 0 – no 1 – yes
29. Thyrotoxicosis in the anamnesis (endocr_03): 0 – no 1 – yes
30. Chronic bronchitis in the anamnesis (zab_leg_01): 0 – no 1 – yes
31. Obstructive chronic bronchitis in the anamnesis (zab_leg_02): 0 – no 1 – yes
32. Bronchial asthma in the anamnesis (zab_leg_03): 0 – no 1 – yes
33. Chronic pneumonia in the anamnesis (zab_leg_04): 0 – no 1 – yes
34. Pulmonary tuberculosis in the anamnesis (zab_leg_06): 0 – no 1 – yes
35. Systolic blood pressure according to Emergency Cardiology Team (S_AD_KBRIG) (mmHg).
36. Diastolic blood pressure according to Emergency Cardiology Team (D_AD_KBRIG) (mmHg).
37. Systolic blood pressure according to intensive care unit (S_AD_ORIT) (mmHg).
38. Diastolic blood pressure according to intensive care unit (D_AD_ORIT) (mmHg).
39. Pulmonary edema at the time of admission to intensive care unit (O_L_POST): 0 – no 1 – yes
40. Cardiogenic shock at the time of admission to intensive care unit (K_SH_POST): 0 – no 1 – yes
41. Paroxysms of atrial fibrillation at the time of admission to intensive care unit, (or at a prehospital stage) (MP_TP_POST): 0 – no 1 – yes
42. Paroxysms of supraventricular tachycardia at the time of admission to intensive care unit, (or at a pre-hospital stage) (SVT_POST): 0 – no 1 – yes
43. Paroxysms of ventricular tachycardia at the time of admission to intensive care unit, (or at a pre-hospital stage) (GT_POST): 0 – no 1 – yes
44. Ventricular fibrillation at the time of admission to intensive care unit, (or at a pre-hospital stage) (FIB_G_POST): 0 – no 1 – yes
45. Presence of an anterior myocardial infarction (left ventricular) (ECG changes in leads V1 – V4 ) (ant_im): 0 – there is no infarct in this location 1 – QRS has no changes 2 – QRS is like QR-complex 3 – QRS is like Qr-complex 4 – QRS is like QS-complex
46. Presence of a lateral myocardial infarction (left ventricular) (ECG changes in leads V5 – V6 , I, AVL) (lat_im): 0 – there is no infarct in this location 1 – QRS has no changes 2 – QRS is like QR-complex 3 – QRS is like Qr-complex 4 – QRS is like QS-complex
47. Presence of an inferior myocardial infarction (left ventricular) (ECG changes in leads III, AVF, II). (inf_im): 0 – there is no infarct in this location 1 – QRS has no changes 2 – QRS is like QR-complex 3 – QRS is like Qr-complex 4 – QRS is like QS-complex
48. Presence of a posterior myocardial infarction (left ventricular) (ECG changes in V7 – V9, reciprocity changes in leads V1 – V3) (post_im): 0 – there is no infarct in this location 1 – QRS has no changes 2 – QRS is like QR-complex 3 – QRS is like Qr-complex 4 – QRS is like QS-complex
49. Presence of a right ventricular myocardial infarction (IM_PG_P): 0 – no 1 – yes
50. ECG rhythm at the time of admission to hospital – sinus (with a heart rate 60-90) (ritm_ecg_p_01): 0 – no 1 – yes
51. ECG rhythm at the time of admission to hospital – atrial fibrillation (ritm_ecg_p_02): 0 – no 1 – yes
52. ECG rhythm at the time of admission to hospital – atrial (ritm_ecg_p_04): 0 – no 1 – yes
53. ECG rhythm at the time of admission to hospital – idioventricular (ritm_ecg_p_06): 0 – no 1 – yes
54. ECG rhythm at the time of admission to hospital – sinus with a heart rate above 90 (tachycardia) (ritm_ecg_p_07): 0 – no 1 – yes
55. ECG rhythm at the time of admission to hospital – sinus with a heart rate below 60 (bradycardia) (ritm_ecg_p_08): 0 – no 1 – yes
56. Premature atrial contractions on ECG at the time of admission to hospital (n_r_ecg_p_01): 0 – no 1 – yes
57. Frequent premature atrial contractions on ECG at the time of admission to hospital (n_r_ecg_p_02): 0 – no 1 – yes
58. Premature ventricular contractions on ECG at the time of admission to hospital (n_r_ecg_p_03): 0 – no 1 – yes
59. Frequent premature ventricular contractions on ECG at the time of admission to hospital (n_r_ecg_p_04): 0 – no 1 – yes
60. Paroxysms of atrial fibrillation on ECG at the time of admission to hospital (n_r_ecg_p_05): 0 – no 1 – yes
61. Persistent form of atrial fibrillation on ECG at the time of admission to hospital (n_r_ecg_p_06): 0 – no 1 – yes
62. Paroxysms of supraventricular tachycardia on ECG at the time of admission to hospital (n_r_ecg_p_08): 0 – no 1 – yes
63. Paroxysms of ventricular tachycardia on ECG at the time of admission to hospital (n_r_ecg_p_09): 0 – no 1 – yes
64. Ventricular fibrillation on ECG at the time of admission to hospital (n_r_ecg_p_10): 0 – no 1 – yes
65. Sinoatrial block on ECG at the time of admission to hospital (n_p_ecg_p_01): 0 – no 1 – yes
66. First-degree AV block on ECG at the time of admission to hospital (n_p_ecg_p_03): 0 – no 1 – yes
67. Type 1 Second-degree AV block (Mobitz I/Wenckebach) on ECG at the time of admission to hospital (n_p_ecg_p_04): 0 – no 1 – yes
68. Type 2 Second-degree AV block (Mobitz II/Hay) on ECG at the time of admission to hospital (n_p_ecg_p_05): 0 – no 1 – yes
69. Third-degree AV block on ECG at the time of admission to hospital (n_p_ecg_p_06): 0 – no 1 – yes
70. LBBB (anterior branch) on ECG at the time of admission to hospital (n_p_ecg_p_07): 0 – no 1 – yes
71. LBBB (posterior branch) on ECG at the time of admission to hospital (n_p_ecg_p_08): 0 – no 1 – yes
72. Incomplete LBBB on ECG at the time of admission to hospital (n_p_ecg_p_09): 0 – no 1 – yes
73. Complete LBBB on ECG at the time of admission to hospital (n_p_ecg_p_10): 0 – no 1 – yes
74. Incomplete RBBB on ECG at the time of admission to hospital (n_p_ecg_p_11): 0 – no 1 – yes
75. Complete RBBB on ECG at the time of admission to hospital (n_p_ecg_p_12): 0 – no 1 – yes
76. Fibrinolytic therapy by Сеliasum 750k IU (fibr_ter_01): 0 – no 1 – yes
77. Fibrinolytic therapy by Сеliasum 1m IU (fibr_ter_02): 0 – no 1 – yes
78. Fibrinolytic therapy by Сеliasum 3m IU (fibr_ter_03): 0 – no 1 – yes
79. Fibrinolytic therapy by Streptase (fibr_ter_05): 0 – no 1 – yes
80. Fibrinolytic therapy by Сеliasum 500k IU (fibr_ter_06): 0 – no 1 – yes
81. Fibrinolytic therapy by Сеliasum 250k IU (fibr_ter_07): 0 – no 1 – yes
82. Fibrinolytic therapy by Streptodecase 1.5m IU (fibr_ter_08): 0 – no 1 – yes
83. Hypokalemia ( < 4 mmol/L) (GIPO_K): 0 – no 1 – yes
84. Serum potassium content (K_BLOOD) (mmol/L).
85. Increase of sodium in serum (more than 150 mmol/L) (GIPER_Na): 0 – no 1 – yes
86. Serum sodium content (Na_BLOOD) (mmol/L).
87. Serum AlAT content (ALT_BLOOD) (IU/L).
88. Serum AsAT content (AST_BLOOD) (IU/L).
89. Serum CPK content (KFK_BLOOD) (IU/L).
90. White blood cell count (billions per liter) (L_BLOOD).
91. ESR (Erythrocyte sedimentation rate) (ROE) (мм).
92. Time elapsed from the beginning of the attack of CHD to the hospital (TIME_B_S): 1 – less than 2 hours 2 – 2-4 hours 3 – 4-6 hours 4 – 6-8 hours 5 – 8-12 hours 6 – 12-24 hours 7 – more than 1 days 8 – more than 2 days 9 – more than 3 days
93. Relapse of the pain in the first hours of the hospital period (R_AB_1_n): 0 – there is no relapse 1 – only one 2 – 2 times 3 – 3 or more times
94. Relapse of the pain in the second day of the hospital period (R_AB_2_n): 0 – there is no relapse 1 – only one 2 – 2 times 3 – 3 or more times
95. Relapse of the pain in the third day of the hospital period (R_AB_3_n): 0 – there is no relapse 1 – only one 2 – 2 times 3 – 3 or more times
96. Use of opioid drugs by the Emergency Cardiology Team (NA_KB): 0 – no 1 – yes
97. Use of NSAIDs by the Emergency Cardiology Team (NOT_NA_KB): 0 – no 1 – yes
98. Use of lidocaine by the Emergency Cardiology Team (LID_KB): 0 – no 1 – yes
99. Use of liquid nitrates in the ICU (NITR_S): 0 – no 1 – yes
100. Use of opioid drugs in the ICU in the first hours of the hospital period (NA_R_1_n): 0 – no 1 – once 2 – twice 3 – three times 4 – four times
101. Use of opioid drugs in the ICU in the second day of the hospital period (NA_R_2_n): 0 – no 1 – once 2 – twice 3 – three times
102. Use of opioid drugs in the ICU in the third day of the hospital period (NA_R_3_n): 0 – no 1 – once 2 – twice
103. Use of NSAIDs in the ICU in the first hours of the hospital period (NOT_NA_1_n): 0 – no 1 – once 2 – twice 3 – three times 4 – four or more times
104. Use of NSAIDs in the ICU in the second day of the hospital period (NOT_NA_2_n): 0 – no 1 – once 2 – twice 3 – three times
105. Use of NSAIDs in the ICU in the third day of the hospital period (NOT_NA_3_n): 0 – no 1 – once 2 – twice
106. Use of lidocaine in the ICU (LID_S_n): 0 – no 1 – yes
107. Use of beta-blockers in the ICU (B_BLOK_S_n): 0 – no 1 – yes
108. Use of calcium channel blockers in the ICU (ANT_CA_S_n): 0 – no 1 – yes
109. Use of а anticoagulants (heparin) in the ICU (GEPAR_S_n): 0 – no 1 – yes
110. Use of acetylsalicylic acid in the ICU (ASP_S_n): 0 – no 1 – yes
111. Use of Ticlid in the ICU (TIKL_S_n): 0 – no 1 – yes
112. Use of Trental in the ICU (TRENT_S_n): 0 – no 1 – yes

__Complications and outcomes of myocardial infarction (Possible target variables)__:

113. Atrial fibrillation (FIBR_PREDS): 0 – no 1 – yes
114. Supraventricular tachycardia (PREDS_TAH): 0 – no 1 – yes
115. Ventricular tachycardia (JELUD_TAH): 0 – no 1 – yes
116. Ventricular fibrillation (FIBR_JELUD): 0 – no 1 – yes
117. Third-degree AV block (A_V_BLOK): 0 – no 1 – yes
118. Pulmonary edema (OTEK_LANC): 0 – no 1 – yes
119. Myocardial rupture (RAZRIV): 0 – no 1 – yes
120. Dressler syndrome (DRESSLER): 0 – no 1 – yes
121. Chronic heart failure (ZSN): 0 – no 1 – yes
122. Relapse of the myocardial infarction (REC_IM): 0 – no 1 – yes
123. Post-infarction angina (P_IM_STEN): 0 – no 1 – yes
124. Lethal outcome (cause) (LET_IS):
    – unknown
    – cardiogenic shock
    – pulmonary edema
    – myocardial rupture
    – progress of congestive heart failure
    – thromboembolism
    – asystole
    – ventricular fibrillation
