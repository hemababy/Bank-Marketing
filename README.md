# Bank-Marketing

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y). From Kaggle.

Kaggle source: [https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing/data](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing/data)

Source: [https://archive.ics.uci.edu/ml/datasets/bank+marketing](https://archive.ics.uci.edu/ml/datasets/bank+marketing)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- Python 3.8 or higher
- Jupyter Notebook
- Git

You can install Python and Jupyter Notebook via Anaconda distribution. Here is the download link: [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)

You can download and install Git from here: [https://git-scm.com/downloads](https://git-scm.com/downloads)

### Installing

A step by step series of examples that tell you how to get a development environment running:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/hemababy/Bank-Marketing.git
```

2. Change the working directory to the project directory:

```bash
cd Bank-Marketing
```

3. Create a virtual environment:

```bash
conda create --name myenv
```

4. Activate the virtual environment:

```bash
conda activate myenv
```

5. Install the required packages:

```bash
pip install -r requirements.txt
```
6. Start Jupyter Notebook:

```bash
jupyter notebook
```

7. Open the Jupyter Notebook file `Bank_Marketing.ipynb` and run the cells.


## Usage


This project is a Jupyter notebook that can be run cell by cell. Here's how to use it:

1. Open the `bank-marketing.ipynb` file in Jupyter Notebook.

2. Run each cell sequentially from top to bottom. You can do this by clicking on a cell and then clicking the 'Run' button in the toolbar, or by pressing `Shift + Enter`.

3. The outputs of each cell, whether they are text, tables, or plots, will be displayed directly below the cell.

4. If you want to modify the code, you can edit the cells directly and then re-run them to see the updated output.

Please note that some cells may depend on the results of previous cells. If you skip a cell or run the cells out of order, you may encounter errors.



## Contributing


Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License. See the [LICENSE.MD](LICENSE.MD) file for details.

## Citation

If you use this project in your research, please cite it as instructed in the [CITATION.cff](CITATION.cff) file.


## Authors

* **Hemalatha Sekar** - *Initial work* - [Hemalatha Sekar](https://github.com/hemababy)

## Acknowledgments

* Thanks to [Kaggle](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing/data) for providing the dataset.
* Thanks to the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing) for hosting the dataset.