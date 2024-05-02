# market_data_processing
This is a example notebook to read markets execution, quotes and ref data and calculate best bid / ask price , mid_price and slippages.

# Creating conda environment
conda env create -f market_data_processing_environment.yaml
# Add conda environment to jupyter notebook kernel 
python -m ipykernel install --user --name=market_data_processing
