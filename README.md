# multrna

Here we predict multifunctionality of microRNA-155 (focusing on 5p arm) by dint of microRNA-GO association prediction

Execution of quick_run folder contents (contains code and data for predictions on functionality of microRNA-155 5p arm)

1. Clone the github repository
2. Move inside quick_run folder
3. Download all files and place them in one folder
4. Set up the environment using environment.yml
5. execute lightGBM.py

Execution of files in full_run folder (contains code and data for full length execution)

1. Clone the github repository
2. Set up the environment using environment.yml
3. Move inside full_run folder
4. Unzip code.zip, data_1.zip and data_2.zip
5. Combine and unrar contents of data_3 folder
6. Place the contents of code folder (by unzipping code.zip), data_1 folder (by unzipping data_1.zip) and data_2 folder (by unzipping data_2.zip) and data_3 folder in one single folder 
7. Execute the following files in order-

  i. fv_a.py
  
  ii. fv_b.py
  
  iii. fv_c.py
  
  iv. merged_embeddings.py
  
   v. mir_go.py
   
  vi. mir_mir.py
  
  vii. join_derived.py
  
  viii. positive_ID.py
  
  ix. hgt_negative_sampling.py
  
  x. blind_data_formation.py
  
  xi. lightGBM.py
  
  xii. prediction.py
  
  xiii. clustering_bp.py
  
  xiv. clustering_mf.py
  
  xv. pcos_go.py
  
  xvi. pcos_pathway.py
  

