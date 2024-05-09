# Real Time Automatic Face Detection Attendance System using Machine Learning

## Abstract

Face recognition has become an integral part of identity verification systems due to its reliability and efficiency. In this project, we present an automated student attendance system based on face recognition, leveraging machine learning techniques. Face recognition technology finds extensive application in security control systems, such as airport security and criminal investigations conducted by organizations like the FBI.

Our proposed system begins with video framing, initiated through a user-friendly interface to activate the camera. Utilizing the Viola-Jones algorithm, the system detects and segments the region of interest (ROI) containing faces from the video frames. Pre-processing techniques are then applied to enhance image quality, including scaling, median filtering for noise reduction, and contrast enhancement using contrast-limited adaptive histogram equalization (CLAHE).

For face recognition, we employ enhanced local binary pattern (LBP) and principal component analysis (PCA) to extract features from facial images. Enhanced LBP offers superior performance compared to the original LBP, mitigating illumination effects and increasing recognition rates. The extracted features from test images are compared with those from training images, and facial images are classified and recognized based on the most optimal algorithmic combination, which includes enhanced LBP and PCA.

Finally, the attendance of recognized students is marked and saved in an Excel file. Additionally, the system allows for on-the-spot registration of unregistered students, with notifications triggered for repeated sign-ins. The recognition accuracy of the system is reported to be 100% for good quality images, 94.12% for low-quality images, and 95.76% for the Yale face database when trained with two images per person.

## Features

- **Real-time Face Detection:** Automatically detects faces in video frames.
- **Pre-processing Techniques:** Enhances image quality for accurate recognition.
- **Feature Extraction:** Utilizes enhanced local binary pattern (LBP) and principal component analysis (PCA) for feature extraction.
- **High Accuracy:** Achieves high recognition accuracy for various image qualities.
- **Attendance Management:** Marks and saves attendance of recognized students.
- **On-the-Spot Registration:** Allows unregistered students to register instantly.
- **Notifications:** Notifies about repeated sign-ins for the same student.

## Installation

1. Clone the repository.
2. Install the required dependencies.
3. Run the main script to start the application.

## Usage

1. Launch the application.
2. Activate the camera through the user-friendly interface.
3. Students' faces will be automatically detected and recognized.
4. Attendance will be marked and saved in an Excel file.
5. Unregistered students can register on the spot.
6. Notifications will be sent for repeated sign-ins.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Pandas

## Contributors

- Saif Ali
- saifali962853@gmail.com
- (https://github.com/Saifali9628)

- Md Ashraf
- 

## License

This project is licensed under the [MIT License](LICENSE).
