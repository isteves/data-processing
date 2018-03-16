#data-processing
### *Repository dedicated to storing and improving datateam processing scripts*

- **Authors**: Dominic Mullen
- **License**: [Apache 2](http://opensource.org/licenses/Apache-2.0)
- [Package source code on Github](https://github.com/NCEAS/data-processing)
- [**Submit Code for review**](https://github.com/NCEAS/data-processing/pulls)

## Style
We generally follow the [tidyverse style conventions](http://style.tidyverse.org/), with the following specific style preferences: 

- underscore for all variable names unless referring to an EML object (i.e. otherEntity, publicationDate, etc.)
- all functions should include argument checks in the form of `stopifnot` statements

## Contributing
### *First Contribution* 
Fork the data-processing repository by clicking on the "Fork" button.  This copies the repository 
to your personal github profile. [fork](images/fork.png)

Navigate to your personal github personal and copy the download with HTTPS: link from the "Clone or
Download" button.  You must do this from your fork on your github profile! [clone](images/clone.png)

Next, open an R session and navigate to: File >> New Project >> Version Control >> Git and paste the
repository url that you copied into the box.  [new project](images/new.png)

## Acknowledgements
Work on this package was supported by:

- The Arctic Data Center: NSF-PLR grant #1546024 to M. B. Jones, S. Baker-Yeboah, J. Dozier, M. Schildhauer, and A. Budden

Additional support was provided by the National Center for Ecological Analysis and Synthesis, a Center funded by the University of California, Santa Barbara, and the State of California.

[![nceas_footer](https://www.nceas.ucsb.edu/files/newLogo_0.png)](http://www.nceas.ucsb.edu)
