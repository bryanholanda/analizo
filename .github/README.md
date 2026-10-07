# Analizo — Historical Open-Source Contributions

**Personal historical fork · Collaborative contributions · Perl · 2013**

[Analizo](https://github.com/analizo/analizo) is a suite of source-code analysis tools. This personal fork preserves early collaborative work; it is not the official project or an actively maintained distribution.

## My recorded contributions

Two commits in the preserved history list **Bryan de Holanda** alongside other contributors:

| Contribution | Evidence |
| --- | --- |
| Export module-level metric details to a CSV file. | [758ebb9 — Writing module metric values into a CSV file](https://github.com/bryanholanda/analizo/commit/758ebb9904f7e7a2d7b6eba9a0df44821f0d3b4d) |
| Make DOT output ordering deterministic for Perl 5.18 and adjust the corresponding test expectation. | [ec4f201 — DOT output: sort hash keys explicitly](https://github.com/bryanholanda/analizo/commit/ec4f2019144b58e2253c2792be75142aeeb4635e) |

The repository's historical [contribution guide](../HACKING) explicitly instructs multi-author patches to list authors with `Signed-off-by` lines. These commits use that convention. They document collaborative participation, not sole authorship of the patches or ownership of the wider Analizo codebase.

## Explore the preserved work

- [`CSV.pm`](../lib/Analizo/Batch/Output/CSV.pm) — batch CSV output implementation.
- [`DOT.pm`](../lib/Analizo/Output/DOT.pm) and [its tests](../t/Analizo/Output/DOT.t) — graph output and test expectations.
- [Original upstream README](../README) — project description, copyright, license information, and acknowledgments.
- [`AUTHORS`](../AUTHORS) and [`HACKING`](../HACKING) — original credits and contributor guidance.

The original root README, code, license information, and project history remain unchanged. This presentation lives in `.github/README.md` so the fork's context is visible without replacing the upstream documentation.

## Maintenance status

This fork is preserved for historical reference and is no longer actively maintained. Compatibility with current dependencies and the status of the historical tests have not been verified. See the [upstream repository](https://github.com/analizo/analizo) for the project itself.
