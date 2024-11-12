# Client-side gene set searching 

Gesel is a gene set database that uses HTTP range requests on static files to perform queries.
We support searching for genes based on the set of interest, for sets based on a gene of interest, and on sets based on the text in their names or descriptions.
By shifting work to the client, we improve reliability and scalability while minimizing server cost and maintenance.

See [here](https://github.com/gesel-inc/gesel-spec) for the file specifications.

[R](https://github.com/gesel-inc/gesel-R) and [Javascript](https://github.com/gesel-inc/gesel.js) clients are available.

To cite the Gesel software, please use:

> Lun et al., (2023). gesel: a JavaScript package for client-side gene set enrichment. Journal of Open Source Software, 8(90), 5777, https://doi.org/10.21105/joss.05777
