seamCarvingAlgorithms.ipynb features a Google Colab notebook with two different codes for image seam-carving & resizing.

The first code, while ineffecient, computes manually the image energy functions from which the seams of the image are determined.
Given a 400 * 400 image, the first code produced the output image in around 5 minutes:
![download (3)](https://github.com/user-attachments/assets/20850840-bfc7-4ea0-85e8-d6438f5bfbc8)
![download (4)](https://github.com/user-attachments/assets/ab0b0c36-84b1-47dc-92a2-4557f37a4d6a)
![download (5)](https://github.com/user-attachments/assets/4545d40a-648b-43ad-b44d-567a81ab5dc5)

The second code avoids nested loops and manual computation, instead, it uses vectorized (optimized) energy computation. Given the following 1428 * 968 image, it produced the following output in about ONE MINUTE of execution:
![download (6)](https://github.com/user-attachments/assets/903b2936-34b6-4307-9635-144144c893c5)
![download (7)](https://github.com/user-attachments/assets/1156cbae-9f35-4e59-8e35-bb7ecf45a0db)
![download (8)](https://github.com/user-attachments/assets/4c2b6e4b-5d60-497b-943e-367c15c4af79)

SUBMITTED BY
120210335 Abdelrahman Amr abdelrahman.abokhalil@ejust.edu.eg
120210389 Salma Amin Noureddin salma.noureddin@ejust.edu.eg
