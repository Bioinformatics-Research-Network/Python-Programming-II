# Python Programming II <img src="https://api.badgr.io/public/badges/5xCf5xpRQqOhRCykbITuLA/image" align="right" alt="logo" width="240" style = "border: none; float: right;">

[![](https://img.shields.io/static/v1?label=Language&message=Python&color=%23fc3)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Type&message=Software&color=darkgoldenrod)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Version&message=0.0.1a&color=darkgreen)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Lifecycle&message=experimental&color=red)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)

**Purpose**: To test your fundamental Python package development skills. 

**Pre-requisites**: *Required*: [Python Programming I](https://github.com/Bioinformatics-Research-Network/Python-Programming-I) 

# Instructions

The following instructions describe the [requirements](#requirements) to complete this task and earn the Python Programming II badge 🏆. They also provide [guidance](#guidance) to help you along the way. 

A few things to keep in mind:

1. Please remember at all times to abide by the [BRN Code of Conduct](https://docs.google.com/document/d/1q06RJbIsyIzLC828A7rBEhtfkujkj9kx7Y118AaWASA/edit?usp=sharing) and [Academic Honesty Policy](https://docs.google.com/document/d/1-Xoko7VDr0lK7olboGQ2CPmEnUTV3WmiDxwQQuGBgiQ/edit). If you notice violations of these policies, please contact codeofconduct@bioresnet.org. 
2. Please remember to [reach out](#getting-help) if you get stuck, find bugs, or even just have a question!

Good luck and have fun! 😊

~ BRN Bot 🤖



## Requirements

**Badge Requirements**:

[![](https://img.shields.io/static/v1?label=Tests&message=Required&color=lightsalmon)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Linting&message=Required&color=lightsalmon)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Coverage&message=Not%20required&color=whitesmoke)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Review&message=Not%20required&color=whitesmoke)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)


**Testing environment**:

[![](https://img.shields.io/static/v1?label=Runs%20on&message=Ubuntu%2022.04%20LTS&color=%235e2750)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Python-Version&message=3.10.4&color=darkturquoise)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)
[![](https://img.shields.io/static/v1?label=Packages-allowed&message=None&color=lightgray)](https://brnteam.notion.site/e8c045b812d842f8bca8e339d22c38ad?v=6245e8becaa641bcafd276e5d910e402)


**Assessment Premise**: 

**TLDR; Take the functions from [Python Programming I](https://github.com/Bioinformatics-Research-Network/Python-Programming-I) and turn them into a package called "bioutils"**

After you completed the tasks your supervisor gave you in [Python Programming I](https://github.com/Bioinformatics-Research-Network/Python-Programming-I), you get a call from HR. Apparently, your functions were so useful that you have been promoted from a Bioinformatics Assistant to Bioinformatics Associate 🚀. Your first task will be to turn your `utils.py` script into a package, `bioutils`, for the whole bioinformatics team to use 🎯. The package should contain all the functions you wrote in `utils.py`, but properly formatted as a package and well-documented. This will enable your colleagues to easily install your package and use the functions contained within!

Users will use your package like so:

```Python
import bioutils as bu

cancer = "ATCGCATACGA"
normal = "ATCCCAGATGA"

bu.protein_variant(cancer, normal)
```


### Automated testing / checking

Prior to releasing the package, your new supervisor will make sure that everything works correctly and that it is well-formatted. She will deploy a bot to run automated checks on your package -- they should produce no errors or warnings.

<details>
<summary>Automated checks</summary>

The bot will initiate an `Python v3.10.4` session and install `bioutils` package by running:

```shell
pip install .
```

Then it will test the package by running:

```shell
pytest
```

Next, it will check the style of the package using `flake8` from the linux command line:

```shell
flake8 .
```

</details>

**Note**: You do not need to write any unit tests as these have already been created for you in the `tests/` folder. 

## Guidance

Most guidance for this assessment is identical to [Python Programming I](https://github.com/Bioinformatics-Research-Network/Python-Programming-I).

### Additional resources

To learn about building and documenting Python packages, visit the following link: [Python Packages Tutorial](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

Additional resources:

1. [Free code camp](https://www.freecodecamp.org/news/build-your-first-python-package/)
2. [The joy of packaging](https://python-packaging-tutorial.readthedocs.io/en/latest/index.html)
3. [Youtube tutorial](https://www.youtube.com/watch?v=qmsTqQbcBNM)

### Getting help

If you find a bug or get confused, please don't hesitate to contact the BRN Skill Assessment maintainers on the **#help-skill-assessments** Slack channel, and they will assist you. 
