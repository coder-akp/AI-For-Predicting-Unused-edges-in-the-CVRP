
# AI for Predicting Unused Edges in the CVRP

A machine learning approach to identify unused edges in Capacitated Vehicle Routing Problem (CVRP) solutions.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AI-For-Predicting-Unused-edges-in-the-CVRP.git
   ```
2. Navigate to project directory:
   ```bash
   cd AI-For-Predicting-Unused-edges-in-the-CVRP
   ```
3. Install required dependencies (see [Dependencies](#dependencies)).

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open `CVRP_jupyter_notebook.ipynb`
3. Follow the notebook instructions to process CVRP instances
4. Modify paths in the notebook to match your local dataset locations

## Project Structure

```
AI-For-Predicting-Unused-Edges-in-the-CVRP/
│
├── Dataset/  
│   ├── Instances/            # VRP problem instance files (.vrp)  
│   │   ├── instance1.vrp  
│   │   ├── instance2.vrp  
│   │   └── ...  
│   ├── Solutions/            # Optimal solutions for instances (.sol)  
│   │   ├── solution1.sol  
│   │   ├── solution2.sol  
│   │   └── ...  
│
├── CVRP_jupyter_notebook.ipynb   # Jupyter Notebook for model training and analysis  
├── .gitignore                    # Files to ignore in version control  
├── LICENSE
├── README.md                      
```

## Dependencies

- Python 3.7+
- Jupyter Notebook
- Required Python packages:
  ```bash
  pip install numpy pandas matplotlib scikit-learn
  ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Standard CVRP dataset sources and formats from [CVRPLIB](https://vrp.galgos.inf.puc-rio.br/)
- Machine learning libraries from the Python ecosystem
- Academic references for CVRP solving approaches
- Collaborators : Abhay Kumar Patel, Hiyabu Ghebresslaise, Megi Cumani, Ahmed Zitouni, Ahmed Zitouni

