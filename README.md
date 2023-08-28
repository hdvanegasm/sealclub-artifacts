# Artifacts - SealClub: Computer-aided Paper Document Authentication

In this repository, you will find all the artifacts for the paper "SealClub: 
Computer-aided Paper Document Authentication". The organization of the
repository is as follows:
- In the `OriginalDocuments` folder you will find all the original documents 
used in the evaluation of the work. The folder will contain files named as
`<index>-<version>.jpg`. The version will be `a` or `b`; the former is the
authentic document and the latter will be the document with one or more
forgeries.
- In the `Data` folder, you will find all the artificially warped documents used
in the evaluation. There you will find folders named `<index>-<version>` which
contain images named `<index>-<version>-<warp_idx>.jpg` that correspond to a
randomly warped version of the `<index>-<version>.jpg` document in the `Data`
folder.

- The `videos` folder contains the output of our analysis tools on videos of printed documents based on `OriginalDocuments`
  
- The `Tamarin` folder contains a proof of the formalized protocol, which can be verified using the Tamarin Prover.

The random warps are generated using the source code in
https://github.com/hdvanegasm/warper.
