# DAHCC HeartRate Dataset

This dataset repository is a small part of the [DAHCC](https://dahcc.idlab.ugent.be/) dataset.
We used the feather files available [here](https://dahcc.idlab.ugent.be/dataset.html) to create the dataset.
We mapped the heart rate data from the feather files to an RDF file using the
[feather-rdf-mapper](https://github.com/argahsuknesib/feather-RDF-mapper) repository.
Here you can find 4 datasets for 4 different patient participants.

## Note
We have used only few observations only (2MB datafiles) for the purpose of this demo. Loading the whole dataset in 
the LDES in LDP solid server has crashed the server and is a known issue to work towards.
