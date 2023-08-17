# HKT Team 6 Project

This project is about inverse design for the molding process of tires. This project is a collaboration of KAIST IsysE/GSDS and HKT. 



## Installation

To use this project, you'll need to follow these steps:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. **Create and activate conda environment:**
   ```sh
   conda create -n hkt python=3.9
   conda activate hkt
3. **Update conda enviroment using yaml file**
   ```sh
   conda env update --file hkt.yaml
4. **Register a new conda env into jupyter notebook**
   ```sh
   python -m ipykernel install --user --name hkt --display-name hkt

## Run the code

Open jupyter notebook with hkt kernel and run inverse_design.ipynb

   ```sh
   jupyter notebook --kernel hkt

