# Logarithmic Laplacian and operators of logarithmic order: boundary expansion, Pohozaev identity and Hadamard formula

Vadim Chekmachev · chekmachev@phystech.edu · ORCID [0009-0009-2982-0532](https://orcid.org/0009-0009-2982-0532)

DOI of all versions: [![10.5281/zenodo.24192858](https://zenodo.org/badge/DOI/10.5281/zenodo.24192858.svg)](https://doi.org/10.5281/zenodo.24192858)

## Abstract

Solutions of the Dirichlet problem for the logarithmic Laplacian L<sub>Δ</sub> with symbol 2 ln |k| have order at most (ln(1/d))<sup>−1/2</sup> near the boundary, where d is the distance to it, and the boundary coefficient plays the role of the normal derivative. In a bounded domain of class C<sup>1,1</sup> every weak solution of the equation L<sub>Δ</sub>u = g with a bounded right-hand side admits an expansion u = β(ln(1/d))<sup>−1/2</sup> + O((ln(1/d))<sup>−1</sup>) with a coefficient β continuous on the boundary. The expansion yields the Pohozaev identity, which for N ≥ 2 had previously been formulated only under the assumption that the boundary limit exists, and the Hadamard formula for simple and multiple eigenvalues and for the torsional rigidity. For any μ, for a solution of L<sub>Δ</sub>z = μz + f, the identity expresses ∫<sub>∂Ω</sub>β<sup>2</sup>(x·ν) dσ in terms of ‖z‖<sup>2</sup> and f, and the derivative of a simple eigenvalue along a deformation field X is equal to −2∫<sub>∂Ω</sub>β<sup>2</sup>(X·ν) dσ for a normalized eigenfunction. From this, the generic simplicity of the spectrum and, for N ≥ 2, the strict decrease of the principal eigenvalue of a ball with an off-center hole as the hole moves away from the center are also derived. In addition, the matrix Pohozaev identity and the simplicity of the spectrum on an interval with a monotone potential are obtained. The boundary expansion, the identity and the formula carry over to operators of logarithmic order, including anisotropic ones and the logarithmic Schrödinger operator (I − Δ)<sup>log</sup>. The proofs rely on a first-order equation for potentials centered on the boundary and on an exact identity comparing the solution with its dilations and translations, and require no a priori regularity of the solution.

Pages: 31. MSC 2020: primary 35R11, secondary 35S15, 35B65, 35P15, 49Q10.

## Files

The repository contains the PDF of the paper, a list of checksums `SHA256SUMS` and an OpenTimestamps timestamp for it (a file with extension `.ots`). The same PDF is published in the Zenodo record of this version.

| File | Size, bytes | SHA-256 | MD5 |
|---|---|---|---|
| `chekmachev-logarithmic-laplacian-and-operators-of-logarithmic-order.pdf` | 854624 | `1bad3447ce51e8bcc5e1010aef972ea4b2f45f6cb3e608102690662cebdafd1e` | `6eb7c85bf4404c1a5356dc7ccd6c438e` |
| `chekmachev-logarithmic-laplacian-and-operators-of-logarithmic-order.pdf.ots` | 770 | `5f948a7dd908cb84a3752bfeb68b4c9102565bf53a449f03b1db36e4dc06fde4` | `1a0894c2a32c88d0e311b3bac4c7b8d5` |

## Version history

Each version of the paper is a separate version of a single Zenodo record with its own DOI. The record's common DOI resolves to the latest version, and the paper should be cited by it.

| Version | Publication date | DOI |
|---|---|---|
| 1.0 (this version) | — | [10.5281/zenodo.24192859](https://doi.org/10.5281/zenodo.24192859) |

## Verification

Checksums. The command `sha256sum -c SHA256SUMS` checks the files of the repository against the list. Zenodo shows each file's MD5 next to it. It is also given in the table above, so whether a file matches the published one can be verified without downloading it.

Timestamp. The `.ots` file is an OpenTimestamps proof: the SHA-256 checksum of the PDF is written into a Bitcoin block, and no one can change the time of that block. To verify, it suffices to drag the PDF and the `.ots` file onto the page https://opentimestamps.org or to run `ots verify` on the proof. The file does not leave the computer in the process.

Signature. The commits of this repository are signed by the author, and GitHub marks them as Verified.

## License

The terms of distribution of the paper and its copy in this repository are given in the [`LICENSE`](LICENSE) file.
