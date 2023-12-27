# Vehicle Number Plate Recognition 

## Objective 
This project focuses on character recognition techniques for vehicle number plate recognition. It employs the K Nearest Neighbor (KNN) algorithm to detect the characters in the vehicle’s number plate. It also successfully identifies the state of origin of the vehicle allowing us document and navigate the vehicles optimally. Moreover, the algorithm allows us to mark the time of entry of the vehicle and store it in a systematic manner. The algorithm provides a methodological solution to keep track of the numerous vehicles entering a premise in an orderly fashion.

## Getting Started
1. Clone the repo
   ```sh
   git clone https://github.com/urjanichakravarti/Vehicle-Number-Plate-Recognition.git
   ```
  
2. Install packages
* opencv
  ```sh
  pip3 install opencv-python
  ```
* numpy
  ```sh
  pip install numpy
  ```

3. Run 'GenData.py' under the 'KNN Data Preparation' folder. Manually train the data by typing the letter (keep caps on) displayed as an image on the screen. In order to restart, press 'escape'. This generates two .txt files - 'classifications.txt' and 'flattened_images.txt'. Insert these text files inside the 'License Plate Recognition' folder.

4. Run 'Main.py'

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. Don't forget to give the project a star! Thanks again!
