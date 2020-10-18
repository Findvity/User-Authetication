## ENSURING SAFETY
This section is for the security point of view. There might be users who may fake their gender/age. This can not only kill the buzz but can also be unsafe. 
To ensure that this doesn't happen, we verify 3 things- ***Age, Gender and Face.***
The person is asked to upload Aadhar image and we convert that into text using Tesseract. 
The *aadhar image* is compared to the ones he/she clicks before using the app for verification using face difference which calculated using difference
in Face encodings. If the gender, age and image match, then the user is **permitted** or else he is asked to enter the correct information.
