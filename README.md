### Numerical Experiments of the paper 
# "Fast Routing under Uncertainty: Adaptive Learning in Congestion Games with Exponential Weights" 

### (Currently under submission at Neurips 2021)

0. The raw data is stored in ../TransportationNetworks-master/. The name of the networks corresponding to the name of the subfolders. When add new networks data (from https://github.com/bstabler/TransportationNetworks), please re-run Create_OMX_matrix_for_data.ipynb)

1. To generate a new instance, use the Passing_data_to_gpickle.ipynb. The new instance, after generated, is stored to ./data/
 
2. To re-run the experiments, use Main experiments.ipynb (by loading the instance that was generated by Passing_data_to_gpickle.ipynb). The results of the experiments are stored in ./solutions/

3. To plot out the results, use Plotting.ipynb.
