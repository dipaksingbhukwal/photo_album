﻿# photo_album

﻿# Please follow below steps to run the application
1.	Pull/download the repository from git: https://github.com/dipaksingbhukwal/photo_album 
2.	Extract the ‘photo_album-master.zip’ file and go to photo_album-master-> photo_album-master directory.
3.	Edit ‘.env’ file for CLOUDINARY_URL to set value:
      CLOUDINARY_URL = “your_cloudinary_url”
4.	Open command prompt in the directory and run ‘npm install’.
5.	Run the program through command prompt using ‘npm start’
6.	Open browser and open link http://localhost:9000/
7.	Upload the images using all three upload options to check the successful upload and overlay upon image retrieval.


Please refer Cloudinary_photo_album_instruction.docx to see the changes made to original photo_album sample project in order to meet below four assessment requirements:

Modify the sample project’s image upload form to:
a. Automatically limit image size to 500x500 pixels on upload.
b. Tag uploaded images (doesn’t matter which tag).

Modify the sample project’s gallery to display 2 additional thumbnails per image:
a. One with the Cloudinary logo as an overlay (watermark).
b. Second with the image saturation increased to 50%.
