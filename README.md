The present CNN was developed during a Machine Learning project within the framework of the DU ITI "Mathematics and applications : research and intercation" of the IRMIA++ institute.

The data of synthetic elliptical galaxies was provided by our supervisor as well as the HST data.

The main script is CNN_training which aims the training of the CNN with different parameters. The trained neural nework is then used in other scripts to analyze its performance.

Comparison_noisy_training allows to compare the predictions of the CNN trained on clean data and trained on noisy data for a given a noisy dataset.

RMSE_noisy_data computes the RMSE in different case of predicted parameters.

Spherical_training_and_radial_profile produces a data set of sphercial galaxies to train the CNN. The radial density profile can be computed for input parameters and the predicted ones by the CNN.

Test_on_HST_image permits to test a certain trained CNN on observational data (here from HST). 
