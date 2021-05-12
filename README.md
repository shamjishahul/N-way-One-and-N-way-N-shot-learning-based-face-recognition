# N-way-One-and-N-way-N-shot-learning-based-face-recognition
Here N classes based one shot learning and N classes N shots learning has been implemented in  aplplication of face authentication .


This has been done as part of the M.Tech Thesis Work on Face recognition using One shot Learning .  Here ORL , FEI and MIT face satabase has been used . The credits for database is given to the owners and not me . I hope it will be useful for my fellow friends. Feel free to use and test as you please.

The ORL Database of Faces (Get it here : https://www.kaggle.com/tavarez/the-orl-database-for-training-and-testing )

The ORL Database of Faces is set of face images taken between April 1992 and April 1994 at the lab. The database was used in the context of a face recognition project carried out in collaboration with the Speech, Vision and Robotics Group of the Cambridge University Engineering Department.

There are ten different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions (open / closed eyes, smiling / not smiling) and facial details (glasses / no glasses). All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position (with tolerance for some side movement).

The MIT-CBCL face(Get it here : http://cbcl.mit.edu/software-datasets/heisele/facerecognition-database.html)
(Credit is hereby given to the Massachusetts Institute of Technology and to the Center for Biological and Computational Learning for providing the database of facial images." The following paper should be cited in case of use : "B. Weyrauch, J. Huang, B. Heisele, and V. Blanz. Component-based Face Recognition with 3D Morphable Models, First IEEE Workshop on Face Processing in Video, Washington, D.C., 2004.")

The MIT-CBCL face recognition database contains face images of 10 subjects. We provide two training sets:
High resolution pictures, including frontal, half-profile and profile view.
Synthetic images (324/subject) rendered from 3D head models of the 10 subjects. The head models were generated by fitting a morphable model to the high-resolution training images. The 3D models are not included in the database.
The test set consists of 200 images per subject. We varied the illumination, pose (up to about 30 degrees of rotation in depth) and the background.

FEI Face Database (Get it here : https://fei.edu.br/~cet/facedatabase.html)

The FEI face database is a Brazilian face database that contains a set of face images taken between June 2005 and March 2006 at the Artificial Intelligence Laboratory of FEI in São Bernardo do Campo, São Paulo, Brazil. There are 14 images for each of 200 individuals, a total of 2800 images. All images are colourful and taken against a white homogenous background in an upright frontal position with profile rotation of up to about 180 degrees. Scale might vary about 10% and the original size of each image is 640x480 pixels. All faces are mainly represented by students and staff at FEI, between 19 and 40 years old with distinct appearance, hairstyle, and adorns.  The number of male and female subjects are exactly the same and equal to 100.
Credits to (Inquiries for further information on dataset ) may be made to:: Dr. Carlos Eduardo Thomaz
Image Processing Laboratory
Department of Electrical Engineering
Centro Universitario da FEI, São Bernardo do Campo, São Paulo, Brazil
Phone: +55 (0) 11 4353-2910
e-mail: cet@fei.edu.br


Train and Validation folder structure :
        Train Folder :{ Total 90 classes 20 shots }
              ORL(1) :  10 Person -----> 20 Images each 
              ORL(2) :  10 Person -----> 20 Images each
              ORL(3) :  10 Person -----> 20 Images each 
              ORL(4) :  10 Person -----> 20 Images each
              ORL(5) :  10 Person -----> 20 Images each 
              ORL(6) :  10 Person -----> 20 Images each
              FEI(1) :  10 Person -----> 20 Images each 
              FEI(2) :  10 Person -----> 20 Images each
              MIT(1) :  10 Person -----> 20 Images each
              
        Val Folder :{ Total 40 classes 20 shots }
              ORL(1) :  10 Person -----> 20 Images each 
              ORL(2) :  10 Person -----> 20 Images each
              FEI(1) :  10 Person -----> 20 Images each 
              FEI(2) :  10 Person -----> 20 Images each
             
        
         
             
                            
                            
