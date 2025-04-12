## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.

STEP 2:Clean the Data Set using Data Cleaning Process.

STEP 3:Apply Feature Encoding for the feature in the data set.

STEP 4:Apply Feature Transformation for the feature in the data set.

STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
## [Data_to_transform]

![image](https://github.com/user-attachments/assets/2eed22ee-ed3d-46e3-8d15-18038c5157b7)

![image](https://github.com/user-attachments/assets/33a66acc-d456-413f-94a5-3aa3e178429b)


  # 1. FUNCTION TRANSFORMATION
• Log Transformation

![image](https://github.com/user-attachments/assets/0b24492a-4dbf-4370-803c-a38e3813cfae)

• Reciprocal Transformation

![image](https://github.com/user-attachments/assets/e21eb199-033d-4646-9907-bbaafb980044)

• Square Root Transformation

![image](https://github.com/user-attachments/assets/e34c8976-f427-46d2-80b6-7e71d640ac29)

• Square Transformation

![image](https://github.com/user-attachments/assets/ecd16fae-02ac-4040-ba2a-258478353482)

  # 2. POWER TRANSFORMATION
• Boxcox method

![image](https://github.com/user-attachments/assets/8668e51c-108c-4456-a97f-ffd04530b38f)

• Yeojohnson method

![image](https://github.com/user-attachments/assets/6be648b5-327f-4c65-9b60-9627f04e7b12)

![image](https://github.com/user-attachments/assets/0280926a-ac84-44f8-a141-b258aaff95d7)

![image](https://github.com/user-attachments/assets/4d18c4e6-a478-4c75-8bcd-6803c7fe9121)

![image](https://github.com/user-attachments/assets/3cc6bd98-5540-43d2-9604-8af9ec3a68b3)

![image](https://github.com/user-attachments/assets/cf640e68-7cc5-4293-8211-b6988b68994d)


## [data.csv]

![image](https://github.com/user-attachments/assets/a0ba19d7-3fef-4c0c-993a-5e86f0ded4dc)

![image](https://github.com/user-attachments/assets/be2540ed-c2c2-4633-8536-1839bda540cc)

![image](https://github.com/user-attachments/assets/fef0d2da-af08-4d79-b9f0-a34589fdd4c0)

## [Encoding data.csv]

![image](https://github.com/user-attachments/assets/3b1a183e-14a8-4dc3-a232-0e6a15b24dcf)

![image](https://github.com/user-attachments/assets/bc3c907f-3f05-410d-a4fb-e44644e314dc)

![image](https://github.com/user-attachments/assets/f7ab50ff-1855-43fd-b396-af49e869a302)

![image](https://github.com/user-attachments/assets/0d4d0cba-527c-4116-92d3-9eed5b87d3cf)

![image](https://github.com/user-attachments/assets/19310903-8d30-45a3-a1f1-e7ef52261b29)

![image](https://github.com/user-attachments/assets/b5abcc30-90dd-4be2-bb87-e6471c0db539)

![image](https://github.com/user-attachments/assets/ebdd3d09-f630-4b81-9758-61d88fea24e2)

# RESULT:

Thus the given data, Feature Encoding, Transformation process and save the data to a file was performed successfully.

       
