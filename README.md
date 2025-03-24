This repo features a Google Colab notebook with two different codes for image seam-carving & resizing.

`seamCarvingAlgorithm.ipynb` manually computes the image enregy functions from which the seams of the image are determined.

  
  Given `Hofflöth(TöVo-Clörath)-2(400x400).jpg`, a 400 * 400 image, the runtime is 5 minutes 34 seconds

![download (3)](https://github.com/user-attachments/assets/20850840-bfc7-4ea0-85e8-d6438f5bfbc8)
![download (4)](https://github.com/user-attachments/assets/ab0b0c36-84b1-47dc-92a2-4557f37a4d6a)
![download (5)](https://github.com/user-attachments/assets/4545d40a-648b-43ad-b44d-567a81ab5dc5)
![Screenshot 2025-03-24 031614](https://github.com/user-attachments/assets/316274b6-e3db-4d3d-9079-e3e629dfab8a)


`seamCarvingAlgorithmOptimized.ipynb` avoids nested loops and manual computation. It instead uses vectorized (optimized) energy computation through `NumPy` and `Numba`. 

  
  Given `Broadway_tower_edit.jpg`, a 1428 * 968 image, its runtime was 57 seconds.

![download (6)](https://github.com/user-attachments/assets/903b2936-34b6-4307-9635-144144c893c5)
![download (7)](https://github.com/user-attachments/assets/1156cbae-9f35-4e59-8e35-bb7ecf45a0db)
![download (8)](https://github.com/user-attachments/assets/4c2b6e4b-5d60-497b-943e-367c15c4af79)
![Screenshot 2025-03-24 030816](https://github.com/user-attachments/assets/6413bc6e-b5af-4f6e-9589-70d34ce4ce76)


### SUBMITTED BY

120210335 Abdelrahman Amr abdelrahman.abokhalil@ejust.edu.eg [GitHub](github.com/bodaqwef)

120210389 Salma Amin Noureddin salma.noureddin@ejust.edu.eg [GitHub](github.com/unearthlyzal)

