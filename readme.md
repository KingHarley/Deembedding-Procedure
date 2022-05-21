`Excitation and reception of magnetostatic surface spin waves in thin conducting ferromagnetic films by coplanar microwave antennas. Part II: Experiment`

This project contains a jupyter notebook file which contains the code which was used to de-embed the raw experimental data.

The data used for the de-embedding is also provided and is located in the `Data` folder. 

The `Data` folder contains numbered folders. The script also contains numbered header cells when specific files need to be loaded in. 

In order to run the de-embedding procedure the cells should be run in order from top to bottom. When the user reaches a cell with a number they will be asked to import 
some raw data files. The data files are proved and numbered as mention above. 

1. Load: `2021-11-11_distance_Antennas_-2.464e-06_Ms=17000_gyro=2.87_A=1.78_Hu12=0_Hub=40_90deg_600Oe_72pts_ref.csv`

2. Load first: `20210920_pf52010611_dev4_cut_rightprobe_2.45kO.s2p`
   Load second: `2020-05-27_pf520181219_dev12_7.0_2407_ref.csv`

3. Load first: `2020-05-27_pf520181219_dev12_1.3157894736842104_600.csv`
   Load second: `2020-05-27_pf520181219_dev12_7.0_2407_ref.csv`

4. Load first: `2021-11-11_distance_Antennas_-2.464e-06_Ms=17000_gyro=2.87_A=1.78_Hu12=0_Hub=40_90deg_600Oe_72pt_sub.csv`
   Load second: `2021-11-11_distance_Antennas_2.464e-06_Ms=17000_gyro=2.87_A=1.78_Hu12=0_Hub=40_90deg_600Oe_72pt_sub.csv`
