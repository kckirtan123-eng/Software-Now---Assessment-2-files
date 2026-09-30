# Software Now — Assessment 2 (team coursework)

Three Python programming exercises with supporting input files. This is an academic source snapshot, not a packaged application or a security product.

| Exercise | Source file | Purpose |
| --- | --- | --- |
| 1 | `Question 1 main code` | Educational text encryption/decryption using a custom shift-based scheme. **Not suitable for protecting real data.** |
| 2 | `Question 2 main code` | Reads Australian temperature CSVs from `temperatures/` and calculates seasonal averages, station ranges and variation. Uses pandas and NumPy imports. |
| 3 | `Question 3` | Turtle graphics experiment drawing recursive geometric patterns. |

`raw_text.txt` and the `temperatures/` directory are exercise inputs. Question 2 is designed to write text summaries to the current working directory when it runs successfully.

## Status and reproduction notes

The source files currently have no `.py` extensions and no pinned environment or automated tests. I have reviewed the code but have **not reproduced a complete run** from this repository. Question 3 contains a visible indentation problem around the input-handling `try` block; it needs correction before execution. Question 2's loader expects station metadata columns in addition to the monthly values, so input validation should be tightened. A future clean-up can add conventional filenames, requirements, sample outputs and tests while preserving the original coursework history.

## Contributors

The repository's GitHub history lists [Bromish03](https://github.com/Bromish03), [kckirtan123-eng](https://github.com/kckirtan123-eng) and [rupesh62](https://github.com/rupesh62). The commit and pull-request history records individual contributions.
