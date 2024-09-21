# Smartphone-Aided-System-for-Point-of-Care-Neonatal-Jaundice-Detection

## Description
This project aims to develop a non-invasive bilirubin meter utilizing smartphone technology to facilitate the timely and accessible diagnosis of neonatal jaundice. Neonatal jaundice, characterized by the yellowing of a newborn’s skin, is caused by the accumulation of excess bilirubin in the bloodstream. Early detection and monitoring are crucial to prevent complications, and our innovative approach leverages smartphone cameras to capture color images of the infant's skin. These images undergo processing and analysis using artificial neural networks to estimate bilirubin levels, allowing for continuous monitoring during phototherapy sessions without the need for painful blood tests.

## Motivation
Jaundice can lead to severe neurological complications or fatalities if left untreated. Traditional diagnostic methods often involve invasive blood tests, which can be uncomfortable and pose challenges, especially in resource-constrained settings. Our goal is to provide a reliable and accessible tool for jaundice monitoring, improving the quality of care for newborns.

## Features
- **Non-invasive:** Early diagnosis of jaundice without intrusive treatments or manual intervention.
- **User-friendly:** Designed for use by healthcare professionals and parents.
- **Edge-based approach:** Utilizes images of the baby to determine bilirubin levels based on skin yellowness.
- **No additional equipment required:** Works well on various devices under typical lighting conditions.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/KVSGVinayak11/Smartphone-Aided-System-for-Point-of-Care-Neonatal-Jaundice-Detection
   ```
2. Navigate to the project directory:
   ```bash
   cd Neonatal-Jaundice-Detection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the application on your smartphone.
2. Capture a clear image of the infant's forehead or skin area.
3. The app will process the image and provide an estimated bilirubin level.

## Data Collection
During the data collection process, images of infants were taken alongside bilirubin reports to train and validate the model. A total of 22 samples were gathered for this purpose.

## Model Development
The model utilizes the k-means algorithm for color clustering and the CIEXYZ color space to calculate the yellow index (YI). A multivariate regression model is then employed to estimate bilirubin levels based on RGB intensities and the yellow index.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
We would like to thank the Department of Electronics & Communication Engineering and the Department of Data Science and Artificial Intelligence at IIIT Naya Raipur for their support in this project.
```

