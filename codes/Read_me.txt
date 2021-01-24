1, Software requirement: tensorflow "1.8.0" 
2, training models: 
"Train_CNN-F.ipynb": train the CNN-F model. Note to change the path in the codes to match the data position. 
"Train_CNN-T.ipynb": train the CNN-T model. Note to change the path in the codes to match the data position. 
3, testing models:
(3.a) "Test_CNN-F_final.ipynb": 
(1) test the saved CNN-F model on different successive events;
(2) Change the data process (SP and NS) by choosing "model" to be 1 or 2;
(3) Change the type of testing datasets with different time intervals by "test_name" (choose from{  total,one_sec,two_sec, half_sec, one_half_sec } )
(4) Note to change the path in the codes to match the data position. 
(3.b) "Test_CNN-T_final.ipynb":
(1) The (1-3) of (3.a) also apply here;
(2) Note to change the path in the codes to match the data position. 
4, "saved_models": this folder saves the trained models that reproduce our previous results. 
(1) ModelA: contains the saved CNN-F model; ModelC: contains the saved CNN-T model. 