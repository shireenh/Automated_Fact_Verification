# Automated_Fact_Verification

Step1: Create Index using file: 

    Indexing_Wikidocs.ipynb

Step2: To Check recall of Index you can create a file using: 

    Recall_of_index.ipynb		

Step3: Retrieve full Text of train files from Wikidoc using:

    Wikidocs_to_json_train_file_text.ipynb

Step4: To Pre-process the Train and Test before Model-1 to get top 5 documents from index and Extract Features:

    Pre-Processing_train_set_Model_1.ipynb
    
    Pre-Processing_test_set_Model_1.ipynb

Step5: For Sentence Selection we will run Model-1:

    Model_1_for_sentence_selection.ipynb

Step6:For Label Prediction Model-2 we will have to pre-process files to extract new features for both train and test files:

    Pre-Processing_files_for_Model_2.ipynb

Step7: Run Model-2 for Label Prediction:

    Model_2_for_Label_prediction.ipynb
