# Face_Recognition
Using neural networks, pre-trained models and APIs to perform face recognition and its various implementations.
  
Uses:  
<img width="601" alt="Screenshot 2021-12-12 at 1 41 37 AM" src="https://user-images.githubusercontent.com/61674750/145690273-3eafc869-f8d5-46e2-8d89-da1b20b033d0.png">  
<img width="441" alt="Screenshot 2021-12-12 at 1 44 46 AM" src="https://user-images.githubusercontent.com/61674750/145690401-fcc7f6cf-0f97-4d23-a513-817177255c39.png"> <img width="441" alt="Screenshot 2021-12-12 at 1 45 24 AM" src="https://user-images.githubusercontent.com/61674750/145690419-b0636f99-4f33-4802-88a0-4033f9c47871.png">


Some commonly used APIs :  
- Amazon Rekognition  
- MS Azure Face  
  
Open Sourced :  
- OpenFace  
- dlib  
- face_recognition.   
  
<img width="302" alt="Screenshot 2021-12-12 at 1 52 17 AM" src="https://user-images.githubusercontent.com/61674750/145690569-310066e1-7da7-4ab7-94b7-634b6c168713.png">  
  
Subsequent developments :  
Viola Jones Algo >> Histogram Oriented Gradients HOG >> CNN 
  
HOG is color independent, as it takes grayscale images and also resistant to lighting. Eg. below    
 <img width="441" alt="Screenshot 2021-12-12 at 1 57 00 AM" src="https://user-images.githubusercontent.com/61674750/145690705-2756fda0-5c5d-4792-b609-bea5e0029b16.png">

### Face Landmarks 

Could be as low as 5 for Snapchat like filters that just use few Face Landmarks to customize and align filters for the snaps and videos.  
Could be as high as 64 or 128.  Eg shown below with 64 face landmarks.   
<img width="441" alt="Screenshot 2021-12-12 at 2 21 43 AM" src="https://user-images.githubusercontent.com/61674750/145691246-8608048f-199c-4cad-8930-d557b6558751.png">  
  
### Face Encodings  

Converting face into face-encodings means simply storing the values of all the measurements of theh face measured between different face-locations found earlier. Usually around 128 face-encodings are used. These represent a vector that point towards a point in the n-dimensional space. Any other input face that generates an encoding which points to a point close enough to the earlier point, it is most probably the same or similar face predicted.  
  
Notes:    
Digital makeup code gives opportunity to highlight various named features stored in the face_locations.  
Similarity code compares input pic with stored pics, to decide which of the stored pics is most similar to the input.
