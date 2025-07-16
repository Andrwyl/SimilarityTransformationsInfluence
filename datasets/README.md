## Datasets

Our experiments span 4 meaning-preserving grammatical transformations:

Given `John liked Mary.`
- Passivization: `Mary was liked by John.`
- Clefting: `It was Mary whom John liked.`
- Topicalization: `Mary, John liked.`
- VP-Topicalization: `Liked Mary, John did.`

We produce 50 sentences pertaining to commonplace historical facts (i.e. Genghis Khan ruled Mongolia). In addition, these sentences are all specifically selected to be simple sentences. The Grammatical Transformation (`grammatical_transformation/`) dataset contains these 50 baseline sentences and for each transformation, 50 of the corresponding transformed sentences. Each transformation's sentences are stored in text files.

To investigate potential 'influence leakage' we make an auxiliary dataset, the Made-Up Entity Dataset (`made_up_entity/`). This dataset is completely identical to the aforementioned dataset, however all of the subjects are replaced with concocted names. `Alexander conquered Persia.` might become `Blojuti conquered Persia.` The structure of this dataset follows exactly the same otherwise.



