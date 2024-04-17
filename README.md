# TargetingPinPoseData
Brief description of what the dataset and code are used for, the domain of research or application (e.g., visual servoing for satellite tracking), and what makes your dataset/codebase significant.

## Description
This repository contains both the synthetic and real-world datasets and the code used to generate them, aimed at improving the precision and efficiency of robotic manipulators through deep learning-based visual servoing. The datasets are designed to support advanced research on motion decoupling in robotic manipulators using a 6 DOF Denso robotic arm equipped with an RGB camera.

### Features
- **Synthetic Dataset**: Generated using RoboDK simulations to ensure diverse scenario coverage under controlled conditions.
- **Real-World Dataset**: Captured with the actual robotic setup to provide real-world applicability and robustness to the models.
- **Image Moments Data**: Includes both image moments and central image moments as features.
- **Camera Pose Labels**: Each entry is labeled with the camera's pose, offering crucial contextual information for visual servoing tasks.

## Dataset Structure
Describe the structure of your dataset here, including the key dimensions, what each dimension represents, and any other pertinent structural information.

### File Descriptions
- `synthetic_data.csv` - Contains the synthetic data points generated from RoboDK.
- `real_world_data.csv` - Contains the real-world data points collected using the Denso manipulator.
- More files description if applicable.

## Installation and Usage
Instructions on how to set up and use the dataset or run the generation code.

### Prerequisites
List of any libraries, tools, or dependencies needed to run the code.
```bash
pip install -r requirements.txt
```
### Running the Code
Instructions on how to run the code to generate the dataset:
```bash 
python generate_synthetic_data.py
python generate_real_data.py
```
## Code
Description of what each script in the repository does:
- `generate_synthetic_data.py`: Generates the synthetic dataset using RoboDK.
- `generate_real_data.py`: Collects real-world data using the Denso robotic setup.

## Authors
- **Your Name** - *Initial work* - [YourGithubProfile](https://github.com/YourGithubProfile)

## License

## Acknowledgments
- Hat tip to anyone whose code was used
- Inspirations
- etc.

## Citations
If you use this dataset or adapt the code in your academic work, please cite it as follows:
@misc{your_citation_key,
author = {Your Name},
title = {Your Dataset Name: A Description},
year = {2024},
publisher = {GitHub},
journal = {GitHub repository},
howpublished = {\url{https://github.com/YourUsername/YourRepositoryName}}
}

## Contact
For any additional questions or requests, you can contact me at:
- Email: youremail@example.com
- Project Link: [https://github.com/YourUsername/YourRepositoryName](https://github.com/YourUsername/YourRepositoryName)
