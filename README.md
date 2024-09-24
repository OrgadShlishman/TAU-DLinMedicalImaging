# TAU-DLinMedicalImaging
Deep Learning in Medical Images Course in TAU

# Code sections
(1) Dataset tools:
  In this section, one can find tools for image enhancement. Specifically, image sharpenning (Done by unsharp masking algorithm [1]).
  In addition, few functions for data augmentation and the arrangmenet of the data in folders can be found in this section.
  

(2) Neural Network for Semantic Segmentation:
  The model is a combination of DINOv2 (Encoder) and SegFormer (Decoder) for semantic segmentation.
  ![image](https://github.com/user-attachments/assets/bd05f179-188d-437c-babd-3bd6653fe4fe)


(3) Neural Network for Semantic Segmentation:
  The model is a combination of DINOv2 [4] (Encoder with linear head).

  
(4) Neural Network for Semantic Segmentation:
  The model is a combination of SegFormer [5] (Only).

# Using the code
(1) Using the dataset tools is function-dependent.
Each function has a usage example, showing how to use it.

(2) Using the Model.
The code has examples and explanations in it (DINOv2 + SegFromer Model).

(3) Using the Model.
The code is similar to the combined model (DINOv2).

(4) Using the Model.
The code is similar to the combined model (SegFromer Model).

# Important Configuration

(1) Make sure you use the correct path to the dataset: "***/RAVIR Dataset"
  The path should be the same one where you locate the dataset.

  
(2) Make sure you use the following structure of the RAVIR dataset:

  ![image](https://github.com/user-attachments/assets/25adc859-af37-4afa-a538-efa8dae23470)

    test:
    
    ![image](https://github.com/user-attachments/assets/b1c3e3f0-e855-4eb9-ae19-fefc8457c00d)

    
    train:
    
    ![image](https://github.com/user-attachments/assets/c9895771-0578-41b0-82ac-66d3866bf6b0)

     
      images:
      
      ![image](https://github.com/user-attachments/assets/89f16833-f119-4b3b-aec7-830f6a287dfb)

      
      mask:
      
      ![image](https://github.com/user-attachments/assets/b9d82bca-bab6-4f29-ad47-9601de746473)  

    
    validation:
    
    ![image](https://github.com/user-attachments/assets/cd85c311-7752-4346-a3b2-7b4b488f7662)

      images:
      
      ![image](https://github.com/user-attachments/assets/d30a0805-1ece-4fec-9db7-d23d68bc69a3)

      
      mask:
      
      ![image](https://github.com/user-attachments/assets/ced478a1-a9ef-4a0c-84db-2b16c9995b5c)


# Additional information
**In this project, the dataset was of RAVIR [2] and was supposed to improve SegRAVIR [3] model results.

# References
[1] https://en.wikipedia.org/wiki/Unsharp_masking


[2] https://ravirdataset.github.io/data/


[3] https://arxiv.org/pdf/2203.14928


[4] https://arxiv.org/abs/2304.07193


[5] https://arxiv.org/abs/2105.15203
