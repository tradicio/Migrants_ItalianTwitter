# Dataset on Italian Twitter discussion on the issue of migration

The present repository contains a dataset consisting of about 5 million of tweets on the issued of migration discussed on the Italian Twittersphere. The dataset present here can be used **only** if the following terms are accepted:

- This dataset is available for research purposes only;
- The papers indicated here in the *References* Section are going to be cited in any research product whose findings are based on this dataset.

## Data Extraction

Data are extracted via the Twitter Streaming API over the period from April 24, 2019 to November 24, 2019, requiring that each tweet contains at least one of the following keywords: _accoglienza_ (hospitality), _apriteiporti_ (open the ports), _chiudiamoiporti_ (close the ports), _immigrazione_ (immigration), _integrazione_ (integration), _migranti_ (migrants), _restiamoumani_ (let’s stay human), _rifugiati_ (refugees), _sbarchi_ (landings), _stopinvasione_ (stop the invasion). 

**Only** the list of tweet IDs is available. The IDs can be then hydrated with software programs specifically designed for retrieving tweet information starting from the tweet ID. An example is the Github repository called [Hydrator](https://github.com/DocNow/hydrator)

## References

References to be cited:

```
bibtex entry:  
@article{2021arXiv210304653R,
       author = {{Radicioni}, T. and {Squartini}, T. and {Pavan}, E. and {Saracco}, F.},
        title = "{Networked partisanship and framing: a socio-semantic network analysis of the Italian debate on migration}",
      journal = {arXiv e-prints},
     keywords = {Computer Science - Social and Information Networks, Physics - Applied Physics},
         year = 2021,
        month = mar,
          eid = {arXiv:2103.04653},
        pages = {arXiv:2103.04653},
archivePrefix = {arXiv},
       eprint = {2103.04653},
 primaryClass = {cs.SI},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2021arXiv210304653R},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

## Data Structure

Within the repository, each txt file contains a list of tweet IDs corresponding to each day of data acquisition. The date format is YYYY-MM-DD. 

For instance the file named _tweets_migrants_italian_twitter_2019-04-24.txt_ contains a list of tweet IDs following the criteria in *Data Extraction* Section and retrieved on April 24th, 2018.
